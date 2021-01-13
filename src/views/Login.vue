<template>
    <div id="login">
        <nav class="panel is-primary">
            <p class="panel-heading">Login</p>
            <div class="panel-block">
                <form>
                    <div class="field">
                        <label class="label">Email</label>
                        <div class="control">
                            <input type="email" placeholder="use: eve.holt@reqres.in" class="input">
                        </div> 
                    </div>
                    <div class="field">
                        <label class="label">Passwords</label>
                        <div class="control">
                            <input type="password" placeholder="any password will do ..." class="input">             >
                        </div>                       
                    </div>
                    <div class="field has-text-right">
                       <button type="submit" class="button is-info">Sign in</button>


                                            
                    </div>
                </form>
            </div>
        </nav>
    </div>
</template>

<script>
export default {
    name: "Login",
};
</script>

<style lang="scss">
#login {
    .panel {
        max-width: 400px;
        margin: 5rem auto 0;

        form {
            width: 100%

        }
    }
}
</style>