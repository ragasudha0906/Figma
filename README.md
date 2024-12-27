# Ex09 Event Registration Web Application
# Date:25-11-2024
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
```
Page 1
<style>
.auth-container {
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  align-items: center;
  margin: 0 auto;
  padding: 57px 8px 141px 24px;
}

.logo-primary {
  aspect-ratio: 3.53;
  object-fit: contain;
  object-position: center;
  width: 100%;
  align-self: stretch;
}

.logo-secondary {
  aspect-ratio: 1.02;
  object-fit: contain;
  object-position: center;
  width: 243px;
  margin-top: 55px;
  max-width: 100%;
}

.auth-button {
  background-color: rgba(72, 202, 222, 1);
  width: 281px;
  max-width: 100%;
  padding: 21px;
  color: rgba(0, 0, 0, 1);
  font: 800 36px Inter, sans-serif;
  text-align: center;
  white-space: nowrap;
}

.login-button {
  margin-top: 133px;
}

.register-button {
  margin-top: 53px;
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

<div class="auth-container">
  <img
    loading="lazy"
    src="https://cdn.builder.io/api/v1/image/assets/1b212e89597745e98d9ae3ca537a2f19/67936953a9dca9ef0a7c92fa3ae634fc7822616a3aa54a5437eb44296fe4c2b5?apiKey=1b212e89597745e98d9ae3ca537a2f19&"
    class="logo-primary"
    alt="Primary company logo"
  />
  <img
    loading="lazy"
    src="https://cdn.builder.io/api/v1/image/assets/1b212e89597745e98d9ae3ca537a2f19/60af536e2fb16d33e4ba33147200c41d0a27af37532a3e0135e85db907e0a1f4?apiKey=1b212e89597745e98d9ae3ca537a2f19&"
    class="logo-secondary"
    alt="Secondary company logo"
  />
  <button class="auth-button login-button" tabindex="0">LOGIN</button>
  <button class="auth-button register-button" tabindex="0">REGISTER</button>
</div>
Page 2
<style>
  .sports-events-container {
    display: flex;
    max-width: 480px;
    width: 100%;
    flex-direction: column;
    overflow: hidden;
    align-items: start;
    margin: 0 auto;
    padding: 52px 19px 324px 38px;
  }
  .sports-title {
    color: rgba(0, 0, 0, 1);
    text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
    text-align: center;
    align-self: stretch;
    font: 800 36px Inter, sans-serif;
  }
  .sports-row {
    display: flex;
    margin-top: 59px;
    gap: 11px;
  }
  .icon-column {
    display: flex;
    flex-direction: column;
  }
  .sport-icon {
    aspect-ratio: 1.5;
    object-fit: contain;
    object-position: center;
    width: 48px;
  }
  .icon-stack {
    display: flex;
    margin-top: 21px;
    flex-direction: column;
    padding: 0 4px;
  }
  .tall-icon {
    aspect-ratio: 0.59;
    object-fit: contain;
    object-position: center;
    width: 48px;
  }
  .sport-icon-spaced {
    aspect-ratio: 1.5;
    object-fit: contain;
    object-position: center;
    width: 48px;
    margin-top: 25px;
  }
  .sports-list {
    display: flex;
    flex-direction: column;
    color: rgba(0, 0, 0, 1);
    text-align: center;
    flex-grow: 1;
    flex-basis: 0;
    width: fit-content;
    margin: auto 0;
    font: 800 36px Inter, sans-serif;
  }
  .indoor-sports {
    display: flex;
    flex-direction: column;
    align-items: start;
    padding: 0 10px;
  }
  .cricket-text {
    margin: 25px 0 0 11px;
  }
  .volleyball-text {
    align-self: stretch;
    margin-top: 23px;
  }
  .relay-text {
    margin-top: 25px;
  }
  .sport-item {
    display: flex;
    margin-top: 24px;
    gap: 8px;
    color: rgba(0, 0, 0, 1);
    white-space: nowrap;
    text-align: center;
    font: 800 36px Inter, sans-serif;
  }
  .sport-name {
    flex-basis: auto;
    flex-grow: 1;
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
  <h1 class="sports-title">
    SPORTS EVENT
    <br />
  </h1>
  <div class="sports-row">
    <div class="icon-column">
      <img
        loading="lazy"
        src="https://cdn.builder.io/api/v1/image/assets/1b212e89597745e98d9ae3ca537a2f19/58cff10779ec041a1e4c4fc69e4193ac3168bd6f358c187ad244fdfd03df819c?apiKey=1b212e89597745e98d9ae3ca537a2f19&"
        class="sport-icon"
        alt="Badminton sport icon"
      />
      <div class="icon-stack">
        <img
          loading="lazy"
          src="https://cdn.builder.io/api/v1/image/assets/1b212e89597745e98d9ae3ca537a2f19/0980c9b1c3ec8657f422e30dcf94dff384329e947c48335a8f9884e519a168de?apiKey=1b212e89597745e98d9ae3ca537a2f19&"
          class="tall-icon"
          alt="Cricket sport icon"
        />
        <img
          loading="lazy"
          src="https://cdn.builder.io/api/v1/image/assets/1b212e89597745e98d9ae3ca537a2f19/58cff10779ec041a1e4c4fc69e4193ac3168bd6f358c187ad244fdfd03df819c?apiKey=1b212e89597745e98d9ae3ca537a2f19&"
          class="sport-icon-spaced"
          alt="Volleyball sport icon"
        />
      </div>
    </div>
    <div class="sports-list">
      <div class="indoor-sports">
        <div>BADMINTON</div>
        <div class="cricket-text">CRICKET</div>
        <div class="volleyball-text">VOLLEY BALL</div>
      </div>
      <div class="relay-text">100Mts-RELAY</div>
    </div>
  </div>
  <div class="sport-item">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/1b212e89597745e98d9ae3ca537a2f19/58cff10779ec041a1e4c4fc69e4193ac3168bd6f358c187ad244fdfd03df819c?apiKey=1b212e89597745e98d9ae3ca537a2f19&"
      class="sport-icon"
      alt="400 meters relay icon"
    />
    <div class="sport-name">400Mts-RELAY</div>
  </div>
  <div class="sport-item">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/1b212e89597745e98d9ae3ca537a2f19/58cff10779ec041a1e4c4fc69e4193ac3168bd6f358c187ad244fdfd03df819c?apiKey=1b212e89597745e98d9ae3ca537a2f19&"
      class="sport-icon"
      alt="High jump sport icon"
    />
    <div class="sport-name">HIGH JUMP</div>
  </div>
  <div class="sport-item">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/1b212e89597745e98d9ae3ca537a2f19/58cff10779ec041a1e4c4fc69e4193ac3168bd6f358c187ad244fdfd03df819c?apiKey=1b212e89597745e98d9ae3ca537a2f19&"
      class="sport-icon"
      alt="Shot put sport icon"
    />
    <div class="sport-name">SHORTPUT</div>
  </div>
  <div class="sport-item">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/1b212e89597745e98d9ae3ca537a2f19/58cff10779ec041a1e4c4fc69e4193ac3168bd6f358c187ad244fdfd03df819c?apiKey=1b212e89597745e98d9ae3ca537a2f19&"
      class="sport-icon"
      alt="Football sport icon"
    />
    <div class="sport-name">FOOT BALL</div>
  </div>
</div>
Page 3
<style>
.registration-container {
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  margin: 0 auto;
  padding: 45px 12px 135px;
}

.registration-title {
  font: 800 36px Inter, sans-serif;
  text-align: center;
  color: #000;
}

.form-group {
  display: flex;
  flex-direction: column;
  width: 100%;
  max-width: 367px;
  margin: 0 auto;
}

.input-field {
  background-color: #F5F5F5;
  padding: 20px;
  margin-top: 19px;
  width: 100%;
  border: none;
  font: 400 24px Inter, sans-serif;
}

.input-row {
  display: flex;
  gap: 7px;
  margin-top: 19px;
}

.input-field-half {
  background-color: #F5F5F5;
  padding: 18px;
  width: 100%;
  border: none;
  font: 400 24px Inter, sans-serif;
}

.submit-button {
  background-color: #52D6EA;
  padding: 20px 16px;
  border: none;
  font: 800 36px Inter, sans-serif;
  color: #000;
  width: 206px;
  margin: 68px auto 0;
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
  <h1 class="registration-title">EVENT REGISTRATION<br />FORM</h1>
  
  <form class="form-group">
    <label for="fullName" class="visually-hidden">Full Name</label>
    <input type="text" id="fullName" class="input-field" placeholder="FULL NAME" required />

    <div class="input-row">
      <div>
        <label for="gender" class="visually-hidden">Gender</label>
        <select id="gender" class="input-field-half" required>
          <option value="">GENDER</option>
          <option value="male">Male</option>
          <option value="female">Female</option>
          <option value="other">Other</option>
        </select>
      </div>
      
      <div>
        <label for="age" class="visually-hidden">Age</label>
        <input type="number" id="age" class="input-field-half" placeholder="AGE" required />
      </div>
    </div>

    <label for="regNumber" class="visually-hidden">Register Number</label>
    <input type="text" id="regNumber" class="input-field" placeholder="REGISTER NUMBER" required />

    <label for="department" class="visually-hidden">Department and Branch</label>
    <input type="text" id="department" class="input-field" placeholder="DEPT & BRANCH" required />

    <label for="email" class="visually-hidden">Email ID</label>
    <input type="email" id="email" class="input-field" placeholder="EMAIL ID" required />

    <label for="event" class="visually-hidden">Event to Register</label>
    <select id="event" class="input-field" required>
      <option value="">EVENT TO BE REGISTER</option>
    </select>

    <button type="submit" class="submit-button">REGISTER</button>
  </form>
</div><style>
.registration-container {
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  margin: 0 auto;
  padding: 45px 12px 135px;
}

.registration-title {
  font: 800 36px Inter, sans-serif;
  text-align: center;
  color: #000;
}

.form-group {
  display: flex;
  flex-direction: column;
  width: 100%;
  max-width: 367px;
  margin: 0 auto;
}

.input-field {
  background-color: #F5F5F5;
  padding: 20px;
  margin-top: 19px;
  width: 100%;
  border: none;
  font: 400 24px Inter, sans-serif;
}

.input-row {
  display: flex;
  gap: 7px;
  margin-top: 19px;
}

.input-field-half {
  background-color: #F5F5F5;
  padding: 18px;
  width: 100%;
  border: none;
  font: 400 24px Inter, sans-serif;
}

.submit-button {
  background-color: #52D6EA;
  padding: 20px 16px;
  border: none;
  font: 800 36px Inter, sans-serif;
  color: #000;
  width: 206px;
  margin: 68px auto 0;
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
  <h1 class="registration-title">EVENT REGISTRATION<br />FORM</h1>
  
  <form class="form-group">
    <label for="fullName" class="visually-hidden">Full Name</label>
    <input type="text" id="fullName" class="input-field" placeholder="FULL NAME" required />

    <div class="input-row">
      <div>
        <label for="gender" class="visually-hidden">Gender</label>
        <select id="gender" class="input-field-half" required>
          <option value="">GENDER</option>
          <option value="male">Male</option>
          <option value="female">Female</option>
          <option value="other">Other</option>
        </select>
      </div>
      
      <div>
        <label for="age" class="visually-hidden">Age</label>
        <input type="number" id="age" class="input-field-half" placeholder="AGE" required />
      </div>
    </div>

    <label for="regNumber" class="visually-hidden">Register Number</label>
    <input type="text" id="regNumber" class="input-field" placeholder="REGISTER NUMBER" required />

    <label for="department" class="visually-hidden">Department and Branch</label>
    <input type="text" id="department" class="input-field" placeholder="DEPT & BRANCH" required />

    <label for="email" class="visually-hidden">Email ID</label>
    <input type="email" id="email" class="input-field" placeholder="EMAIL ID" required />

    <label for="event" class="visually-hidden">Event to Register</label>
    <select id="event" class="input-field" required>
      <option value="">EVENT TO BE REGISTER</option>
    </select>

    <button type="submit" class="submit-button">REGISTER</button>
  </form>
</div>
Page 4
<style>
.thank-you-container {
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  font-family: Inter, sans-serif;
  color: rgba(0, 0, 0, 1);
  font-weight: 800;
  margin: 0 auto;
  padding: 37px 26px 94px;
}

.logo-image {
  aspect-ratio: 4.31;
  object-fit: contain;
  object-position: center;
  width: 375px;
}

.thank-you-header {
  font-size: 36px;
  text-align: center;
  align-self: center;
  margin-top: 170px;
  width: 286px;
}

.event-text {
  font-size: 24px;
}

.contact-info {
  background-color: rgba(245, 245, 245, 1);
  width: 358px;
  max-width: 100%;
  font-size: 24px;
  margin: 258px 0 0 17px;
  padding: 6px 4px 53px;
}

.contact-detail {
  font-weight: 500;
  font-size: 16px;
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

<div class="thank-you-container">
  <img
    loading="lazy"
    src="https://cdn.builder.io/api/v1/image/assets/1b212e89597745e98d9ae3ca537a2f19/09e074d1a119ed32c1adab028880a86b57f34be20c2630059aa71a4cdd628766?apiKey=1b212e89597745e98d9ae3ca537a2f19&"
    class="logo-image"
    alt="Saveetha Engineering College Logo"
  />
  <div class="thank-you-header">
    THANK YOU
    <br />
    <span class="event-text">FOR REGISTERING EVENT</span>
  </div>
  <div class="contact-info">
    CONTACT US:
    <br />
    EMAIL ID:
    <span class="contact-detail">
      SAVEETHAENGCLG@GMAIL.COM
    </span>
    <br />
    ADDRESS:
    <br />
    <span class="contact-detail">
      SAVEETHAENGINEERINGCOLLEGE,
    </span>
    <br />
    <span class="contact-detail">
      THADALAM,SRIPREMBATHUR
    </span>
    <br />
    <br />
  </div>
</div>
```
# OUTPUT:
![Screenshot_(106) 1](https://github.com/user-attachments/assets/8a382f97-e26f-42c4-8024-3f086774a6ba)

# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
