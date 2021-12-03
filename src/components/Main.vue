<template>
<div class="Background">
    <div class="App_Left">
        <img src="https://www.dailytech.in.th/wp-content/uploads/2017/05/twitter.png" alt="">
    </div>

    <div class="App_Right">
        <div class="content">
            <h1>Happening Now</h1>
            <h2>Join Twitter Today.</h2>
            <b-button variant="outline-secondary" class="button">
                <b-icon icon="Google"></b-icon>
                Sign up with Google
            </b-button>
            <b-button variant="outline-secondary" class="button">
                <b-icon icon="app"></b-icon>
                Sign up with Apple
            </b-button>
            <hr />
            <b-button variant="outline-success" class="button">Sign up with your email</b-button>
            <p class="FormField_Link">By signing up, you agree to the Terms of Service and Privacy Policy,
                <br />including Cookie Use.</p>
        </div>
        <div class="content">
            <h5>Already have an accout</h5>
            <b-button variant="outline-secondary" class="button">Register</b-button>
        </div>
    </div>
</div>
</template>

<script>
export default {

}
</script>

<style>
img {
    height: 100%;
    width: 100%;
}

.content {
    display: flex;
    flex-direction: column;
    justify-content: center;
    margin: 20px;
}

.button {
    margin: 10px;
}

.Background {
    height: 100vh;
    display: flex;
    margin: 0px;
    padding: 0px;
}

.App_Left {
    width: 50%;
}

.App_Right {
    width: 50%;
    padding: 25px 40px;
    overflow: auto;
    display: flex;
    flex-direction: column;
}

.FormField_Link {
    color: #66707D;
    text-decoration: none;
    /* display: inline-block; */
    /* border-bottom: 1.5px solid #225E62; */
    /* padding-bottom: 5px; */
}
</style>
