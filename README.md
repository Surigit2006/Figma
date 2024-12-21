# Ex09 Event Registration Web Application
# Date:
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:
page 1
```

<style>
.sports-container {
  background-color: #fff;
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  color: #fff;
  margin: 0 auto;
  font: 700 32px Instrument Sans, sans-serif;
}

.sports-wrapper {
  display: flex;
  flex-direction: column;
  position: relative;
  min-height: 956px;
  width: 100%;
  align-items: center;
  padding: 38px 41px 236px;
}

.sports-bg {
  position: absolute;
  inset: 0;
  height: 100%;
  width: 100%;
  object-fit: cover;
  object-position: center;
}

.sports-banner {
  aspect-ratio: 5.59;
  object-fit: contain;
  object-position: center;
  width: 100%;
  align-self: stretch;
}

.sports-logo {
  aspect-ratio: 1.11;
  object-fit: contain;
  object-position: center;
  width: 100%;
  margin-top: 37px;
  max-width: 333px;
}

.sports-title {
  position: relative;
  color: #0e52fd;
  font-weight: 400;
  margin-top: 22px;
  border: 1px solid #000;
}

.login-btn {
  position: relative;
  background-color: #ea2121;
  margin-top: 67px;
  width: 172px;
  max-width: 100%;
  padding: 9px 14px 19px;
  border: 1px solid #000;
  cursor: pointer;
  text-align: center;
}

.register-btn {
  position: relative;
  background-color: #eb2828;
  width: 200px;
  max-width: 100%;
  margin: 66px 0 -47px;
  padding: 2px 8px 25px;
  cursor: pointer;
  text-align: center;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
</style>

<div class="sports-container">
  <div class="sports-wrapper">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/e21677d79e9257266fe0c83c13089757f055ec20a0b2f6115e22cca736b79f9b?placeholderIfAbsent=true&apiKey=db86ac91c6bb4de690ab53062e84463a"
      class="sports-bg"
      alt="Sports day background"
    />
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/bdd1a70b46f022b0c7f7d8e18d249de44407f417245e0930ccfed94f9a741990?placeholderIfAbsent=true&apiKey=db86ac91c6bb4de690ab53062e84463a"
      class="sports-banner"
      alt="Sports day banner"
    />
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/0c8c02ad2e7789214a9a30b35ed36a86bb66cf01bfc32154d69cc62468ebf8ad?placeholderIfAbsent=true&apiKey=db86ac91c6bb4de690ab53062e84463a"
      class="sports-logo"
      alt="Sports day logo"
    />
    <h1 class="sports-title">SPORTS DAY EVENTS</h1>
    <button class="login-btn" tabindex="0">LOGIN</button>
    <button class="register-btn" tabindex="0">REGISTER</button>
  </div>
</div>
```

page 2

```

<style>
.sports-events-container {
  background-color: #fff;
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  font-family: Instrument Sans, sans-serif;
  margin: 0 auto;
}

.events-wrapper {
  display: flex;
  flex-direction: column;
  position: relative;
  min-height: 956px;
  width: 100%;
  align-items: start;
  padding: 61px 50px 347px;
}

.background-image {
  position: absolute;
  inset: 0;
  height: 100%;
  width: 100%;
  object-fit: cover;
  object-position: center;
}

.events-title {
  position: relative;
  color: #0e40f4;
  text-shadow: 0 4px 4px rgba(0, 0, 0, 0.25);
  font-size: 32px;
  font-weight: 700;
  border: 1px solid #000;
}

.events-list {
  position: relative;
  color: #000;
  font-size: 24px;
  font-weight: 600;
  width: 341px;
  margin: 85px 0 -69px;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
</style>

<div class="sports-events-container">
  <div class="events-wrapper">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/db86ac91c6bb4de690ab53062e84463a/63c5b85e73cb0c11d21b31b96830776f647387923ef83334540bdbe5e255c9a2?apiKey=db86ac91c6bb4de690ab53062e84463a&"
      class="background-image"
      alt="Sports day events background"
    />
    <h1 class="events-title">SPORTS DAY EVENTS</h1>
    <div class="events-list" role="list">
      CIRCKET
      <br />
      <br />
      FOOTBALL
      <br />
      <br />
      VOLLEY BALL
      <br />
      <br />
      KABBADI
      <br />
      <br />
      100 METERS
      <br />
      <br />
      200 METERS
      <br />
      <br />
      400 METERS
      <br />
      <br />
      4X 100 RELAY
      <br />
      <br />
    </div>
  </div>
</div>

```



Page 3
```

<style>
.registration-container {
  background-color: #fff;
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  color: #000;
  margin: 0 auto;
  font: 600 20px Instrument Sans, sans-serif;
}

.registration-wrapper {
  display: flex;
  flex-direction: column;
  position: relative;
  min-height: 956px;
  width: 100%;
  align-items: start;
  padding: 60px 39px 230px;
}

.background-image {
  position: absolute;
  inset: 0;
  height: 100%;
  width: 100%;
  object-fit: cover;
  object-position: center;
}

.form-title {
  position: relative;
  color: rgb(226, 60, 26);
  text-shadow: 0 4px 4px rgba(0, 0, 0, 0.25);
  font-size: 24px;
  font-weight: 700;
  align-self: stretch;
}

.form-field {
  position: relative;
  background-color: #fff9f9;
  width: 299px;
  max-width: 100%;
  padding: 9px;
  margin-top: 25px;
}

.form-field-alt {
  position: relative;
  background-color: #fffdfd;
  width: 299px;
  max-width: 100%;
  padding: 9px;
  margin-top: 34px;
}

.submit-button {
  position: relative;
  background-color: rgb(249, 21, 21);
  align-self: center;
  width: 183px;
  max-width: 100%;
  font-size: 32px;
  color: #fff;
  font-weight: 700;
  margin: 84px 0 -46px;
  padding: 5px 15px;
  border: none;
  cursor: pointer;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
</style>

<div class="registration-container">
  <div class="registration-wrapper">
    <img
      class="background-image"
      src="https://cdn.builder.io/api/v1/image/assets/db86ac91c6bb4de690ab53062e84463a/8d1f87c517b3635e696421b9bde92e20798aa3affd6557547e4631a16cdba7d8?apiKey=db86ac91c6bb4de690ab53062e84463a&"
      alt=""
      loading="lazy"
    />
    <form>
      <h1 class="form-title">EVENT REGISTRATION FORM</h1>
      
      <label for="fullName" class="visually-hidden">Full Name</label>
      <input type="text" id="fullName" class="form-field" placeholder="FULL NAME" required />
      
      <label for="gender" class="visually-hidden">Gender</label>
      <select id="gender" class="form-field" required>
        <option value="">Gender</option>
        <option value="male">Male</option>
        <option value="female">Female</option>
        <option value="other">Other</option>
      </select>
      
      <label for="age" class="visually-hidden">Age</label>
      <input type="number" id="age" class="form-field" placeholder="Age" required />
      
      <label for="registerNo" class="visually-hidden">Register Number</label>
      <input type="text" id="registerNo" class="form-field" placeholder="Register no" required />
      
      <label for="department" class="visually-hidden">Department</label>
      <input type="text" id="department" class="form-field-alt" placeholder="Department" required />
      
      <label for="phone" class="visually-hidden">Phone Number</label>
      <input type="tel" id="phone" class="form-field-alt" placeholder="Phone no" required />
      
      <label for="email" class="visually-hidden">Email</label>
      <input type="email" id="email" class="form-field-alt" placeholder="Email" required />
      
      <label for="events" class="visually-hidden">Events to Register</label>
      <select id="events" class="form-field-alt" required>
        <option value="">No events to register</option>
      </select>
      
      <button type="submit" class="submit-button">REGISTER</button>
    </form>
  </div>
</div>

```

page 4

```
<style>
.thank-you-section {
  background-color: #fff;
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  font-family: Instrument Sans, sans-serif;
  font-weight: 700;
  margin: 0 auto;
}

.content-wrapper {
  display: flex;
  flex-direction: column;
  position: relative;
  min-height: 956px;
  width: 100%;
  align-items: start;
  padding: 37px 46px 63px;
}

.background-image {
  position: absolute;
  inset: 0;
  height: 100%;
  width: 100%;
  object-fit: cover;
  object-position: center;
}

.logo {
  aspect-ratio: 5.59;
  object-fit: contain;
  object-position: center;
  width: 341px;
  position: relative;
}

.thank-you-message {
  position: relative;
  color: #000;
  font-size: 32px;
  align-self: center;
  margin-top: 172px;
  width: 265px;
  text-align: center;
}

.message-text {
  font-size: 24px;
}

.contact-info {
  position: relative;
  color: #E50E3C;
  font-size: 24px;
  margin-top: 350px;
}

.contact-detail {
  font-size: 20px;
  color: #000;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
</style>

<div class="thank-you-section">
  <div class="content-wrapper">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/db86ac91c6bb4de690ab53062e84463a/d17a35fb2e961cea4eb793742b3a577a1f2703a7f87081fee4557b92162c1c1e?apiKey=db86ac91c6bb4de690ab53062e84463a&"
      class="background-image"
      alt=""
    />
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/db86ac91c6bb4de690ab53062e84463a/dd439a5e195667b70f2772bbda7f375429dfca1ccc3b2abb79825d78fbc41ac2?apiKey=db86ac91c6bb4de690ab53062e84463a&"
      class="logo"
      alt="Saveetha College Logo"
    />
    <div class="thank-you-message">
      THANKYOU
      <br />
      <br />
      <span class="message-text">we all are eagerly</span>
      <br />
      <span class="message-text">waiting for your</span>
      <br />
      <span class="message-text">participation in the</span>
      <br />
      <span class="message-text">sports event</span>
    </div>
    <div class="contact-info">
      CONTACT US
      <br />
      <span class="contact-detail">saveethacollage@gmail.com</span>
      <br />
      <span class="contact-detail">7896754328</span>
      <br />
      <span class="contact-detail">8956737854</span>
    </div>
  </div>
</div>

```

# OUTPUT:

![Screenshot 2024-12-21 103704](https://github.com/user-attachments/assets/b3f28ee6-bc9a-4388-98e6-41467eb9b4dc)

![Screenshot 2024-12-21 103558](https://github.com/user-attachments/assets/a2b0bfe1-8232-4919-b058-eb1a7b7ea033)


![Screenshot 2024-12-21 103724](https://github.com/user-attachments/assets/9d356eb2-7d6a-4c87-91fd-d6433ed205f5)



![Screenshot 2024-12-21 103751](https://github.com/user-attachments/assets/71e31fc8-9f11-468b-8aff-40395941b584)


# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
