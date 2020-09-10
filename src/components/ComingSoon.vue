<template>
  <div class="container">
    <section class="content">

      <div class="headline">
        <h1 class="wordmark">Henceforward</h1>
        <div class="arrows"></div>
      </div>

      <p class="p1">
        this will be a resource for all who seek to see social equity & racial justice in our lifetime by any <span class="highlight">means</span> necessary.
      </p>

      <!-- Begin Mailchimp Signup Form -->
      <div id="mc_embed_signup" class="subscribe-form-wrapper">
        <h2>Sign up to be notified when we launch.</h2>
        <form
          action="https://henceforward.us17.list-manage.com/subscribe/post?u=5e29881f7dd3fb2b1c3468c95&amp;id=4006e5e4cc"
          method="post"
          id="mc-embedded-subscribe-form"
          name="mc-embedded-subscribe-form"
          class="subscribe-form validate"
          target="_blank"
          novalidate>
          <div class="subscribe-form__field mc-field-group">
            <input type="text" placeholder="Your name" value="" name="NAME" class="subscribe-form__input required" id="mce-NAME">
          </div>
          <div class="subscribe-form__field mc-field-group">
            <input type="email" placeholder="Your email address" value="" name="EMAIL" class="subscribe-form__input required email" id="mce-EMAIL">
          </div>
          <div id="mce-responses" class="clear">
            <div class="response" id="mce-error-response" style="display:none"></div>
            <div class="response" id="mce-success-response" style="display:none"></div>
          </div>
          <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
          <div style="position: absolute; left: -5000px;" aria-hidden="true"><input type="text" name="b_5e29881f7dd3fb2b1c3468c95_4006e5e4cc" tabindex="-1" value=""></div>
          <input type="submit" value="Count me in" name="subscribe" id="mc-embedded-subscribe" class="subscribe-form__button">
        </form>
      </div>
      <!--End mc_embed_signup-->
    </section>

    <footer>
      EST 2020
      twitter logo
      insta logo
    </footer>
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
  display: flex;
  flex-flow: column nowrap;
  justify-content: space-between;
  min-width: 100vw;
  min-height: 100vh;

  .headline {
    display: flex;
    flex-flow: row nowrap;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 2.0em;
  }

  .arrows {
    width: 106px;
    height: 40px;
    background-image: url(../assets/arrows_large.png);
    background-repeat: no-repeat;
    background-position: top left;
  }

  .content {
    display: flex;
    flex-flow: column wrap;
    justify-content: center;
    flex: 2 0 auto;
    padding: 0 10%;
    background: #fff;
  }

  footer {
    flex: 0 1 25vh;
    align-self: flex-end;
    width: 100%;
    padding: 10%;
    background: #000;
    color: #fff;
  }

  .subscribe-form-wrapper {
    margin: 5em 0 0 0;
  }

  .subscribe-form {
    display: flex;
    flex-flow: row nowrap;

    &__field {
      flex: 0 1 auto;
      padding: 0;
      margin: 0 10px 0 0;
      height: 100%;
      width: 100%;
      max-width: 28.0em;
      min-width: 20.0em;
    }

    &__input,
    &__button {
      height: 44px;
      padding: 0 15px;
      margin: 0;
      border-radius: 12px;
    }

    &__input {
      width: 100%;
      border: 1px solid #767676;
      background-color: #f2f2f2;
      font: 500 1.6em/1.2 'Roboto', sans-serif;

      &:focus {
        outline: none;
        border: 1px solid #ff0000;
      }
    }

    &__button {
      flex: 0 1 auto;
      width: auto;
      max-width: 10.0em;
      border: 1px solid #000;
      background: #000;
      color: #fff;
      font-size: 1.2em;
      font-weight: 700;
      cursor: pointer;
      text-transform: uppercase;

      &:focus {
        outline: none;
        border: 1px solid #ff0000;
      }

      &:hover {
        opacity: 0.8;
      }
    }
  }

  @media screen and (max-width: 600px) {
    .content {
      padding: 0 7%;
      margin-bottom: 5em;
    }

    .headline {
      flex-flow: column-reverse nowrap;
      align-items: start;
    }

    .arrows {
      width: 52px;
      height: 20px;
      margin: 5.0em 0 7.0em;
      background-image: url(../assets/arrows_small.png);
    }

    .subscribe-form {
      flex-flow: column nowrap;

      &__field {
        max-width: 100%;
        margin-right: 0;
        margin-bottom: 10px;
      }

      &__input {
        font-size: 3.2em;
      }

      &__button {
        font-size: 2.4em;
      }
    }
  }

  @media screen and (max-height: 800px) {
    footer {
      flex: 0 1 10vh;
    }
  }
}
</style>
