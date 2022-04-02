<h2>What is AMP Email? 📧</h2>

AMP for email allows senders to include AMP components inside rich engaging emails, making modern app functionality available within email. The AMP email format provides a subset of AMPHTML components for use in email messages, that allows recipients of AMP emails to interact dynamically with content directly in the message.

More than 270 billion emails are sent every day, it is the pillar of many consumer and enterprise workflows. However the content that is sent in an email message is still limited – messages are static, can become out of date, and are not actionable without opening a browser. AMP email seeks to enhance and modernize the email experience through added support for dynamic content and interactivity while keeping users safe.

<br>

<b>Multiple Mockups have been created for testing 🧪</b>

<ul>
  <li>For Emeritus</li>
  <li>Feedback form</li>
  <li>AMP based forms</li>
  <li>Quiz</li>
  <li>Emeritus Mockup</li>
  <li>Crocs Mockup</li>
</ul>


```<!doctype html>
<html ⚡4email data-css-strict>
<head>
  <meta charset="utf-8">
  <script async src="https://cdn.ampproject.org/v0.js"></script>
  <style amp4email-boilerplate>body{visibility:hidden}</style>
  <style amp-custom>
    h1 {
      margin: 1rem;
    }
  </style>
</head>
<body>
  <h1>Hello, I am an AMP EMAIL!</h1>
</body>
</html>
```


This is a Sample AMP Based Email. The Syntax is quite different then plain HTML 🙂

<h2>AMP Playgrounds ⛹️</h2>

AMP Playgrounds is a platform where a user can draft AMP emails, see a live preview, and have your emails sent to your Mail.ru account.

<a href="https://postmaster.mail.ru/amp/">AMP Email Playgrounds</a>

AMP Based Mockup for a Carousel 🏞🎑🌉

```
<!doctype html>
<html ⚡4email>
<head>
  <meta charset="utf-8">
  <script async src="https://cdn.ampproject.org/v0.js"></script>
  <script async custom-element="amp-carousel" src="https://cdn.ampproject.org/v0/amp-carousel-0.1.js"></script>
  <style amp4email-boilerplate>body{visibility:hidden}</style>
  <style amp-custom>
    .carousel-preview {
      	margin-top: 15px;
         text-align: center;
    }
  </style>
</head>
<body>
   <amp-carousel id="carousel-with-preview"
    width="450"
    height="300"
    layout="responsive"
    type="slides">
    <amp-img src="https://ampproject-b5f4c.firebaseapp.com/examples/images/image1.jpg"
      width="450"
      height="300"
      layout="responsive"
      alt="apples"></amp-img>
    <amp-img src="https://ampproject-b5f4c.firebaseapp.com/examples/images/image2.jpg"
      width="450"
      height="300"
      layout="responsive"
      alt="lemons"></amp-img>
    <amp-img src="https://ampproject-b5f4c.firebaseapp.com/examples/images/image3.jpg"
      width="450"
      height="300"
      layout="responsive"
      alt="blueberries"></amp-img>
  </amp-carousel>
  <div class="carousel-preview">
    <button on="tap:carousel-with-preview.goToSlide(index=0)">
      <amp-img src="https://ampproject-b5f4c.firebaseapp.com/examples/images/image1.jpg"
        width="60"
        height="40"
        alt="apples"></amp-img>
    </button>
    <button on="tap:carousel-with-preview.goToSlide(index=1)">
      <amp-img src="https://ampproject-b5f4c.firebaseapp.com/examples/images/image2.jpg"
        width="60"
        height="40"
        alt="lemons"></amp-img>
    </button>
    <button on="tap:carousel-with-preview.goToSlide(index=2)">
      <amp-img src="https://ampproject-b5f4c.firebaseapp.com/examples/images/image3.jpg"
        width="60"
        height="40"
        alt="blueberries"></amp-img>
    </button>
  </div>
</body>
</html>
```

Ping me in for Any Queries 🤔
