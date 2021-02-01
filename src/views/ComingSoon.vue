<template>
  <div class="coming-soon">
    <section class="coming-soon__intro">
      <icon-mark />
      <h1 class="wordmark">Henceforward,</h1>
      <p class="about">
        we give more. We give smarter – to give social equity and racial justice
        a chance to be realized in our lifetime.
      </p>
    </section>

    <!-- Begin Mailchimp Signup Form -->
    <div id="mc_embed_signup" class="coming-soon__form--wrapper">
      <h2 class="coming-soon__form__header">Get notified when we launch.</h2>
      <form
        action="https://henceforward.us17.list-manage.com/subscribe/post?u=5e29881f7dd3fb2b1c3468c95&amp;id=4006e5e4cc"
        method="post"
        id="mc-embedded-subscribe-form"
        name="mc-embedded-subscribe-form"
        class="coming-soon__form validate"
        target="_blank"
        novalidate>
        <div class="coming-soon__form__field mc-field-group">
          <input
            type="text"
            placeholder="Name"
            value=""
            name="NAME"
            class="coming-soon__form__input required"
            id="mce-NAME">
        </div>
        <div class="coming-soon__form__field mc-field-group">
          <input
            type="email"
            placeholder="Email"
            value=""
            name="EMAIL"
            class="coming-soon__form__input required email"
            id="mce-EMAIL">
        </div>
        <div id="mce-responses" class="clear">
          <div class="response" id="mce-error-response" style="display:none"></div>
          <div class="response" id="mce-success-response" style="display:none"></div>
        </div>
        <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
        <div style="position: absolute; left: -5000px;" aria-hidden="true"><input type="text" name="b_5e29881f7dd3fb2b1c3468c95_4006e5e4cc" tabindex="-1" value=""></div>
        <input type="submit" value="Count me in" name="subscribe" id="mc-embedded-subscribe" class="coming-soon__form__button">
      </form>
    </div>
    <!--End mc_embed_signup-->

    <footer class="coming-soon__footer">
      <div class="socials">
        <a class="socials__link" href="/" target="_blank"><icon-insta /></a>
        <a class="socials__link" href="/" target="_blank"><icon-twitter /></a>
      </div>
      <icon-est />
    </footer>
  </div>
</template>

<script>
import IconMark from '@/components/icons/mark.vue'
import IconInsta from '@/components/icons/insta.vue'
import IconTwitter from '@/components/icons/twitter.vue'
import IconEst from '@/components/icons/est.vue'

export default {
  name: 'ComingSoon',
  components: {
    IconMark,
    IconInsta,
    IconTwitter,
    IconEst
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.coming-soon {
  display: flex;
  flex-flow: column nowrap;
  min-width: 100%;
  min-height: 100%;

  &__intro,
  &__form--wrapper,
  &__footer {
    padding-left: 20px;
    padding-right: 20px;
  }

  &__intro {
    display: flex;
    flex-flow: column nowrap;
    flex: 0 0 auto;

    padding-top: 30px;
    padding-bottom: 30px;

    font: 400 4.5em 'Jomhuria', sans-serif;
    line-height: 80%;

    .icon-mark {
      margin-bottom: 30px;
      width: 44px;
      height: 20px;
    }

    .wordmark {
      font-weight: 400;
      color: #130729;
      text-transform: uppercase;
      word-wrap: break-word;
    }

    .about {
      color: #A19CA9;
    }
  }

  &__form {
    display: flex;
    flex-flow: row wrap;

    &--wrapper {
      display: flex;
      flex-flow: column nowrap;
      flex: 1 1 auto;
      padding-top: 20px;
      padding-bottom: 20px;
      background: #130729;
    }

    &__header {
      margin: 0 0 15px 0;
      font: 400 1.4em 'Merriweather Sans', sans-serif;
      color: #fff;
    }

    &__field {
      flex: 0 1 auto;
      padding: 0;
      margin: 0 10px 0 0;
      height: 100%;
      width: 100%;
      max-width: 210px;
      min-width: 200px;
    }

    &__input {
      height: 45px;
      width: 100%;
      padding: 12px;
      margin: 0;
      border: 1px solid #fff;
      background-color: #fff;
      font: 500 1.2em/1.2 'Merriweather', sans-serif;

      &:focus {
        outline: none;
        border: 1px solid #ff0000;
      }
    }

    &__button {
      flex: 0 1 auto;
      height: 45px;
      width: auto;
      max-width: 100%;
      margin: 0;
      padding: 15px 20px;
      border-radius: 20px;
      border: 1px solid #42807C;
      background: #42807C;
      font: 400 1.2em 'Merriweather Sans', sans-serif;
      color: #fff;
      text-transform: uppercase;
      cursor: pointer;

      &:focus {
        outline: none;
        border: 1px solid #ff0000;
      }

      &:hover {
        opacity: 0.8;
      }
    }
  }

  &__footer {
    padding-top: 20px;
    padding-bottom: 30px;
    display: flex;
    flex-flow: row nowrap;
    flex: 0 0 auto;
    justify-content: space-between;
    color: #fff;
    background-color: #130729;
    background-size: auto;
    background-image: url(../assets/diagonal-tile.png);
    background-repeat: repeat-x;
    background-position: bottom left;

    .socials {
      display: flex;
      flex-flow: row nowrap;

      &__link {
        display: block;
        margin-right: 20px;

        &:last-child {
          margin-right: 0;
        }

        &:hover {
          opacity: 0.5;
        }
      }
    }

    .est {
      color: #fff;
    }

    // &::after {
    //   content: "";
    //   width: 100%;
    //   height: 20px;
    //   position: absolute;
    //   bottom: 0;
    //   left: 0;
    //   background-color: red;
    //   background-image: url(../assets/diagonal-tile.png);
    //   background-repeat: repeat-x;
    //   background-position: bottom left;
    // }
  }

  @media screen and (max-width: 600px) {
    &__form__field {
      max-width: 100%;
      min-width: 100%;
      margin-right: 0;
      margin-bottom: 10px;
    }
  }

  @media screen and (min-width: 375px) {
    &__intro {
      padding-top: 50px;
      padding-bottom: 50px;

      .icon-mark {
        margin-bottom: 50px;
      }

    }
  }

  @media screen and (min-width: 768px) {
    &__intro,
    &__form--wrapper,
    &__footer  {
      padding-left: 100px;
      padding-right: 100px;
    }

    &__intro {
      padding-top: 80px;
      padding-bottom: 80px;
      font-size: 9.0em;

      .icon-mark {
        margin-bottom: 80px;
        width: 81px;
        height: 37px;
      }
    }

    &__form--wrapper {
      padding-top: 50px;
      padding-bottom: 50px;
    }

    &__footer {
      padding-top: 45px;
      padding-bottom: 50px;
    }
  }
}
</style>
