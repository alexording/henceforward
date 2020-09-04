<template>
  <div class="container">
    <h1 class="wordmark">Henceforward</h1>

    <!-- Begin Mailchimp Signup Form -->
    <div id="mc_embed_signup">
      <form action="https://henceforward.us17.list-manage.com/subscribe/post?u=5e29881f7dd3fb2b1c3468c95&amp;id=4006e5e4cc" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
        <div id="mc_embed_signup_scroll">
          <h2>Move forward with us</h2>
          <div class="mc-field-group">
            <label for="mce-EMAIL">Email </label>
            <input type="email" placeholder="you@email.com" value="" name="EMAIL" class="required email" id="mce-EMAIL">
          </div>
          <div id="mce-responses" class="clear">
            <div class="response" id="mce-error-response" style="display:none"></div>
            <div class="response" id="mce-success-response" style="display:none"></div>
          </div>
          <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
          <div style="position: absolute; left: -5000px;" aria-hidden="true"><input type="text" name="b_5e29881f7dd3fb2b1c3468c95_4006e5e4cc" tabindex="-1" value=""></div>
          <div class="clear"><input type="submit" value="Subscribe" name="subscribe" id="mc-embedded-subscribe" class="button"></div>
        </div>
      </form>
    </div>
    <!--End mc_embed_signup-->
  </div>
</template>

<script>
export default {
  name: 'ComingSoon',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.container {
  width: 80%;
  margin: 0 auto;

  #mc-embedded-subscribe {
    margin: 10px 0 0 0;
    border: 0;
    background: #fff;
    color: #000;
    padding: 0.4em 1.2em;
    border-radius: 0.4em;
    cursor: pointer;
    font: 400 1.6em/1.2 'Oswald', sans-serif;

    &:hover {
      opacity: 0.8;
    }
  }
}
</style>
