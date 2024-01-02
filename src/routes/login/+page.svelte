<script>
    export let form;
    import google from '$lib/assets/icons/google.png'
</script>

<section class="h-screen variant-filled-surface py-16 flex flex-col justify-end items-center">
    <form method="post" action="?/OAuth2">
        <button href="/" class="btn variant-filled-primary rounded-full px-16" type="submit">
            <span><img src={google} alt=""></span>
            <span>Get started</span>
        </button>
    </form>
</section>