<!--Subscription-->
<section class="newsletter">
  <div class="container">
    <div class="newsletter-form-wrap">
      <h2 class="newsletter-title section-title">Newsletter</h2>
      <p class="newsletter-text">
        Every week we will send you new designs and information about sales.
      </p>
      <form class="newsletter-form">
        <div class="newsletter-name-wrap">
          <input
            class="newsletter-input"
            type="text"
            name="user-name"
            minlength="2"
            maxlength="16"
            id="user-name"
            placeholder="Name"
          />
        </div>

        <div class="newsletter-email-wrap">
          <input
            class="newsletter-input"
            type="email"
            name="user-email"
            id="user-email"
            placeholder="E-mail"
          />
          <svg class="newsletter-error-icon" width="24" height="24">
            <use href="../images/subscription/newsletter-icons.svg#newsletter-icon-error"></use>
          </svg>
        </div>

        <input
          class="newsletter-check visually-hidden"
          type="checkbox"
          name="user-subscribe"
          value="true"
          id="user-subscribe"
        />
        <label class="newsletter-check-text" for="user-subscribe">
          <span class="newsletter-check-span">
            <svg class="newsletter-check-icon" width="13" height="13">
              <use href="../images/subscription/newsletter-icons.svg#newsletter-check-bird"></use>
            </svg>
          </span>
          Agree to subscribe to the newsletter
        </label>
        <button class="newsletter-submit-btn" type="submit">Send</button>
      </form>
    </div>

    <div class="newsletter-img-wrap">
      <picture>
        <source
          srcset="
            ../images/subscription/newsletter-img-desk-1x.jpg 1x,
            ../images/subscription/newsletter-img-desk-2x.jpg 2x
          "
          media="(min-width:1440px)"
        />
        <source
          srcset="
            ../images/subscription/newsletter-img-tab-1x.jpg 1x,
            ../images/subscription/newsletter-img-tab-2x.jpg 2x
          "
          media="(min-width:768px)"
        />
        <source
          srcset="
            ../images/subscription/newsletter-img-mob-1x.jpg 1x,
            ../images/subscription/newsletter-img-mob-2x.jpg 2x
          "
          media="(min-width:320px)"
        />
        <source
          srcset="
            ../images/subscription/newsletter-img-mob-1x.jpg 1x,
            ../images/subscription/newsletter-img-mob-2x.jpg 2x
          "
          media="(max-width:319px)"
        />
        <img
          src="./images/newsletter/newsletter-img-desk-1x.jpg"
          alt="sofa picture"
          width="704"
        />
      </picture>
    </div>

  </div>
</section>
