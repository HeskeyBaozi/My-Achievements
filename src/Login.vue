<template>
    <div>
        <h1 class="title">My Achievements</h1>
        <form accept-charset="UTF-8" action="/session" method="post">
            <label for="login_field">
                Username or email address
            </label>
            <input id="login_field" name="login" tabindex="1" type="text"/>
            <label for="password">
                Password <a href="/password_reset" class="label-link">Forgot password?</a>
            </label>
            <input class="form-control form-control input-block" id="password" name="password" tabindex="2"
                   type="password">
            <input class="btn btn-primary btn-block" name="commit" tabindex="3"
                   type="submit" value="Sign in"/>
        </form>
    </div>
</template>
<style>


</style>
<script>
    export default{}

</script>
