body {
  margin: 0;
}

.page {
  font-family: "Inter", Arial, sans-serif;
  min-width: 1100px;
  max-width: 1600px;
  margin: 0 auto;
  font-size: 16px;
  line-height: 20px;
}

.header {
  background-image: url(../images/background_header.svg);
  background-color: #ffffff;
  background-repeat: no-repeat;
  background-size: cover;
  min-height: 720px;
  max-height: 800px;
  height: 100vh;
  display: flex;
  flex-direction: column;
  padding: 30px 80px 40px;
  box-sizing: border-box;
  position: relative;
}

.nav {
  display: flex;
  justify-content: space-between;
}

.nav__links {
  display: flex;
  flex-direction: row;
  gap: 20px;
  list-style-type: none;
  margin: 30px 80px auto 0;
}

.nav__link {
  text-decoration: none;
  color: black;
}

.nav__logo {
  width: 105px;
  height: 39px;
  position: relative;
  left: -30px;
}

.header__content {
  min-height: 720px;
  max-height: 800px;
  height: 100vh;
  position: relative;
}

.header__content-title-wrapper {
  margin: 120px 0 0 80px;
}

.header__title {
  max-width: 709px;
  margin-top: 183px;
  display: flex;
  flex-direction: column;
  font-family: Inter;
  font-style: normal;
  font-weight: 500;
  font-size: 58px;
  line-height: 72px;
  letter-spacing: 1px;
}

.span-accent {
  display: block;
  font-family: Noto Serif;
  font-style: italic;
  font-weight: normal;
  font-size: 58px;
  line-height: 72px;
  color: #2f80ed;
}

.header__description {
  font-family: Noto Serif;
  font-style: normal;
  font-weight: normal;
  font-size: 20px;
  line-height: 30px;
  max-width: 683px;
  margin-top: 20px;
}

.header__image {
  width: 646px;
  height: 568px;
  position: absolute;
  top: 124px;
  right: 5px;
}

.header__footer {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-top: auto;
}

.header__footer-list {
  display: flex;
  flex-direction: column;
  list-style-type: none;
}
.header__footer-item {
  font-family: Inter;
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 20px;
  color: #838383;
}
.header__paragraph {
  font-family: Inter;
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 20px;
  color: #838383;
  margin: 0;
}

.recipes {
  background-color: #0a2750;
  background-image: url(../images/background_recipes.svg);
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  min-height: 720px;
  max-height: 860px;
  height: 100vh;
  margin: 0;
  padding: 30px 80px 40px;
  overflow: hidden;
  box-sizing: border-box;
  display: flex;
  flex-direction: column;
}

.recipes__header {
  margin: 100px 0 0 80px;
}

.recipes__videos-felx {
  display: flex;
  justify-content: center;
}

.recipes__title {
  color: #ffffff;
  font-family: "Inter";
  font-style: normal;
  font-weight: 500;
  font-size: 44px;
  line-height: 52px;
  margin: 0;
  padding-top: 100px;
  max-width: 500px;
}

.recipes__subtitle {
  color: #ffffff;
  font-family: "Noto Serif";
  font-style: normal;
  font-weight: normal;
  font-size: 20px;
  line-height: 30px;
  padding-top: 24px;
  margin-bottom: 0;
  max-width: 438px;
}

.recipes__videos {
  display: flex;
  width: 480px;
  height: 273px;
  margin: 80px 0 215px 0;
  margin: 80px auto 215px;
}

.recipes__video-item {
  display: flex;
  gap: 40px;
  list-style-type: none;
}

.recipes__iframe {
  border-style: none;
  border-radius: 10px;
}

.recipes__video-caption {
  color: white;
  font-family: "Inter";
  font-style: normal;
  font-weight: 500;
  font-size: 20px;
  line-height: 30px;
  display: flex;
  justify-content: space-between;
}

.reservation {
  background-color: #d9e7ff;
  background-image: url(../images/background_reservation.svg);
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  min-height: 720px;
  max-height: 860px;
  height: 100vh;
  margin: 0;
  padding: 100px 80px 120px;
  overflow: hidden;
  box-sizing: border-box;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.reservation__title {
  font-family: Inter;
  font-style: normal;
  font-weight: 500;
  font-size: 44px;
  line-height: 52px;
  margin: 0;
  padding-top: 100px;
  margin: 0 auto 80px;
  display: flex;
  align-items: center;
}

.reservation__form {
  display: flex;
  flex-direction: column;
  justify-content: center;
  box-sizing: border-box;
  max-width: 385px;
  padding: 80px 0 120px;
}

.reservation__form-admin {
  display: flex;
  flex-direction: column;
  justify-content: center;
  margin: 0;
  padding: 0;
}

.form__fieldset {
  display: flex;
  justify-content: center;
  flex-direction: column;
  border: none;
  margin: 0;
  padding: 0;
}

.form__fieldset__el_container {
.form__fieldset-el-container {
  padding: 0 0 32px;
  margin: 0;
  border: none;
  max-width: 385px;
  width: 100vw;
  display: flex;
  justify-content: center;
  flex-direction: column;
}

.form__label {
  font-family: Inter;
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 20px;
  margin: 0;
  padding: 0 0 8px;
}

.form__input {
  border-radius: 4px;
  border-color: #838383;
  border: 1px;
  font-family: Inter;
  font-style: normal;
  font-weight: normal;
  font-size: 20px;
  line-height: 30px;
  max-width: 385px;
  max-height: 60px;
  height: 100vh;
  width: 100vw;
  margin: 0;
  padding: 15px 20px;
  box-sizing: border-box;
}

.form__handlers {
  padding: 0 0 32px;
  margin: 0;
  border: none;
}

.form__button {
  border-radius: 4px;
  opacity: 1;
  transition: opacity 0.3s ease;
  font-family: Inter;
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 20px;
  max-width: 385px;
  height: 60px;
  width: 100vw;
  margin: 0;
  padding: 0;
  background-color: #3c9cdb;
  color: white;
}

.form__button:hover {
  opacity: 0.7;
}

.form__checkbox__container {
.form__checkbox-container {
  margin: 0;
  padding: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  border: none;
}

.form__checkbox {
  border-radius: 2px;
  background-color: #2f80ed;
  width: 20px;
  height: 20px;
}

.form__checkbox:checked {
  background-image: url(../images/check.svg);
}

.form__checkbox__label {
.form__checkbox-label {
  display: block;
  margin: auto 0;
  font-size: 20px;
  line-height: 30px;
}

.form__checkbox__label-right {
.form__checkbox-label-right {
  display: inline;
  font-size: 14px;
  padding-left: 12px;
  font-family: Inter;
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 20px;
}