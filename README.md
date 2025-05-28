<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>The Learning Curve</title>
  <link
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"
    rel="stylesheet"
  />
  <style>
    body {
      font-family: 'Georgia', serif;
      line-height: 1.6;
      margin: 0;
      padding: 0;
      background: #f9f9f9;
      color: #333;
    }

    header {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 1rem;
      background: #003366;
      padding: 1.2rem 1rem;
    }

    header .logo {
      width: 42px;
      height: 42px;
      background: #0055a5;
      border-radius: 6px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-weight: 700;
      color: white;
      font-family: Arial, sans-serif;
      font-size: 1.2rem;
      user-select: none;
      box-shadow: 0 0 8px #004080;
    }

    header div.text-block {
      color: white;
      text-shadow: 1.5px 1.5px 3px rgba(0, 0, 0, 0.75);
      text-align: left;
    }

    header h1 {
      margin: 0;
      font-size: 2.3rem;
      font-weight: 800;
      line-height: 1.1;
    }

    header p {
      margin: 0;
      font-size: 1.1rem;
      font-style: italic;
    }

    section {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
      background: white;
      box-shadow: 0 0 15px rgba(0, 0, 0, 0.05);
      margin-bottom: 2rem;
      border-radius: 8px;
    }

    h2 {
      color: #003366;
      margin-bottom: 1rem;
      border-bottom: 3px solid #0055a5;
      padding-bottom: 0.3rem;
    }

    ul {
      list-style: none;
      padding-left: 0;
    }

    ul li {
      margin-bottom: 0.8rem;
      padding-left: 1.8rem;
      position: relative;
      font-size: 1rem;
    }

    ul li::before {
      content: '\f058'; /* FontAwesome check icon */
      font-family: "Font Awesome 6 Free";
      font-weight: 900;
      position: absolute;
      left: 0;
      color: #0055a5;
      top: 0.1rem;
    }

    .enroll-button {
      display: inline-block;
      padding: 0.7rem 1.8rem;
      background-color: #0055a5;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      margin-top: 1rem;
      font-weight: 600;
      box-shadow: 0 3px 6px rgba(0, 85, 165, 0.6);
      transition: background-color 0.3s ease;
    }

    .enroll-button:hover {
      background-color: #004080;
    }

    .testimonial,
    .faq {
      background: #eef3f7;
      padding: 1rem;
      margin-bottom: 1rem;
      border-left: 4px solid #003366;
      border-radius: 4px;
    }

    /* Icons for subjects list */
    .subjects ul li {
      padding-left: 2.2rem;
    }

    .subjects ul li::before {
      content: '\f19d'; /* FontAwesome book icon */
      font-family: "Font Awesome 6 Free";
      font-weight: 900;
      position: absolute;
      left: 0;
      color: #0077cc;
      top: 0.2rem;
    }

    .contact p {
      font-size: 1rem;
      margin: 0.3rem 0;
    }

    footer {
      background: #003366;
      color: white;
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
    }

    /* Responsive */
    @media (max-width: 600px) {
      header {
        flex-direction: column;
        text-align: center;
      }

      header div.text-block {
        text-align: center;
      }
    }
  </style>
</head>

<body>
  <header>
    <div class="logo">TLC</div>
    <div class="text-block">
      <h1>The Learning Curve</h1>
      <p>Online and Offline Tuition for Classes KG to 12</p>
    </div>
  </header>

  <section class="info">
    <h2>Welcome to The Learning Curve</h2>
    <p>
      We are a group of experienced educators offering expert tuition in all
      subjects from KG to 12. We aim to provide concept-based, result-oriented
      education through flexible online, offline, and home tuition classes.
    </p>
    <a
      class="enroll-button"
      href="https://forms.gle/AEKjxybn7GxYR7xv7"
      target="_blank"
      >Enroll Now</a
    >
  </section>

  <section class="subjects">
    <h2>Subjects Offered</h2>
    <ul>
      <li><strong>KG to Class 8:</strong> All Subjects (English, Maths, Science, SST, Hindi, etc.)</li>
      <li><strong>Class 9 to 12 (All Streams):</strong> English, Mathematics, Physics, Chemistry, Biology, Accountancy, Business Studies, Economics, Applied Mathematics</li>
    </ul>
  </section>

  <section class="details">
    <h2>Timings & Class Details</h2>
    <ul>
      <li>
        <strong>Group Classes:</strong><br />
        KG to Class 8 (All Subjects)<br />
        Duration: 1 hour per session<br />
        Batch size: 6–8 students<br />
        Frequency: 6 days a week
      </li>
      <li>
        <strong>Subject-wise Classes (Class 6 to 12):</strong><br />
        Duration: 1 hour per session<br />
        Batch size: 6–8 students<br />
        Frequency: 3 days a week per subject
      </li>
      <li>
        <strong>One-on-One Classes:</strong><br />
        Personalized sessions tailored to the student’s pace and needs<br />
        Flexible scheduling as per availability
      </li>
      <li>
        <strong>Offline & Home Tuitions:</strong><br />
        We also offer offline classes and private home tuition based on location
        and availability.
      </li>
    </ul>

    <h2>Why Choose Us?</h2>
    <ul>
      <li>Experienced and passionate teachers dedicated to your child’s success.</li>
      <li>Small batches ensure personalized attention and active participation.</li>
      <li>Concept-based, exam-focused teaching that builds strong foundations.</li>
      <li>Flexible timings to suit your child’s schedule.</li>
      <li>Regular tests and feedback to monitor progress.</li>
      <li>Supportive and encouraging learning environment.</li>
      <li>Options for online, offline, and home tuition classes.</li>
    </ul>

    <h2>Our Fees & Their Worth</h2>
    <p>
      Our fees reflect the quality and personalized attention your child
      receives. We believe in providing value beyond just teaching—our programs
      are designed to build confidence, improve understanding, and help
      students excel academically.
    </p>
    <p>
      Investing in your child’s education with us means giving them the tools for
      lifelong learning and success.
    </p>

    <h2>Trial Classes</h2>
    <p>
      We offer <strong>free trial classes</strong> so you can experience our
      teaching approach and decide if it’s the right fit for your child before
      enrolling. This way, you can make an informed decision with no commitment
      upfront.
    </p>
  </section>

  <section class="testimonials">
    <h2>What Parents & Students Say</h2>
    <div class="testimonial">
      <p>
        <strong>Ritika Sharma (Parent):</strong> "My daughter improved a lot in
        Maths and Science within just two months. The teachers are very
        supportive and skilled."
      </p>
    </div>
    <div class="testimonial">
      <p>
        <strong>Rahul Mehta (Class 11):</strong> "I really like the one-on-one
        sessions. They explain everything in a simple and clear way. I feel more
        confident now."
      </p>
    </div>
  </section>

  <section class="faqs">
    <h2>Frequently Asked Questions</h2>
    <div class="faq">
      <p>
        <strong>Q: Can I choose between online, offline, or home tuition?</strong
        ><br />
        A: Yes, we offer all three formats depending on availability and your
        preference.
      </p>
    </div>
    <div class="faq">
      <p>
        <strong>Q: What happens if my child misses a class?</strong><br />
        A: We provide makeup classes or support through notes and recordings
        whenever possible.
      </p>
    </div>
    <div class="faq">
      <p>
        <strong>Q: Do you give regular tests?</strong><br />
        A: Yes, we conduct periodic assessments to track progress and
        understanding.
      </p>
    </div>
  </section>

  <section class="contact">
    <h2>Contact Us</h2>
    <p>Email: thelearningcurvetlc@gmail.com</p>
    <p>Phone: 8604482492</p>
  </section>

  <footer>
    <p>&copy; 2022 The Learning Curve. All rights reserved.</p>
  </footer>
</body>

</html>
