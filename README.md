<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Joseck Premier Services</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background: #f0f4f8;
      color: #333;
    }
    header {
      background: #004aad;
      color: white;
      padding: 20px 10px;
      text-align: center;
    }
    .logo {
      font-weight: 700;
      font-size: 1.8em;
      letter-spacing: 2px;
      text-transform: uppercase;
      font-family: 'Arial Black', Arial, sans-serif;
      margin-bottom: 4px;
    }
    .tagline {
      font-style: italic;
      font-size: 1.1em;
      color: #cde2ff;
      margin-top: 0;
    }
    main {
      max-width: 900px;
      margin: 20px auto;
      padding: 0 15px 40px;
    }
    section {
      background: white;
      margin-bottom: 30px;
      border-radius: 10px;
      padding: 20px 25px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    h2 {
      color: #004aad;
      border-bottom: 3px solid #004aad;
      padding-bottom: 8px;
      margin-top: 0;
    }
    ul {
      list-style: none;
      padding-left: 0;
      margin: 0;
    }
    li {
      margin-bottom: 12px;
      padding-left: 30px;
      position: relative;
      font-weight: 600;
    }
    li:before {
      content: '\\2713';
      position: absolute;
      left: 8px;
      color: #004aad;
      font-weight: 900;
    }
    footer {
      background: #004aad;
      color: white;
      text-align: center;
      padding: 15px 10px;
      font-size: 0.9em;
    }
    .whatsapp-button {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #25D366;
      color: white;
      padding: 14px 22px;
      border-radius: 50px;
      font-weight: bold;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
      text-decoration: none;
      display: flex;
      align-items: center;
      gap: 8px;
      font-size: 1em;
      transition: background-color 0.3s ease;
    }
    .whatsapp-button:hover {
      background: #1ebe57;
    }
    .whatsapp-icon {
      width: 20px;
      height: 20px;
      fill: white;
    }
    @media (max-width: 600px) {
      main {
        margin: 10px;
        padding: 0 10px 30px;
      }
      .whatsapp-button {
        padding: 12px 16px;
        font-size: 0.9em;
      }
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">Joseck Premier Services</div>
    <p class="tagline">Your trusted online services partner</p>
  </header>

  <main>
    <section id="services">
      <h2>Our Services</h2>
      <ul>
        <li>KRA Filing Returns</li>
        <li>HELB Applications & Clearance</li>
        <li>KUCCPS Course Applications</li>
        <li>eCitizen Services (Birth Certificates, IDs, Good Conduct)</li>
        <li>NHIF, NSSF, CRB, NTSA Services</li>
        <li>And many more tailored services!</li>
      </ul>
    </section>

    <section id="contact">
      <h2>Contact Us</h2>
      <p>Phone/WhatsApp: <strong>+254 717 592 710</strong></p>
      <p>Email: <strong>joseckservices@example.com</strong></p>
      <p>Location: Online-based, available countrywide</p>
    </section>
  </main>

  <a
    href="https://wa.me/254717592710?text=Hello%2C%20I%20visited%20your%20website%20and%20would%20like%20to%20know%20more%20about%20your%20online%20services.%20Please%20assist%20me."
    class="whatsapp-button"
    target="_blank"
    rel="noopener noreferrer"
    aria-label="Chat with Joseck Premier Services on WhatsApp"
  >
    <svg class="whatsapp-icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
      <path d="M20.52 3.48A11.86 11.86 0 0012.01.01C6.27.01 1.56 4.74 1.56 10.47a9.33 9.33 0 001.42 4.74L.06 23.94l8.9-2.36a9.34 9.34 0 004.95 1.36c5.75 0 10.47-4.73 10.47-10.47 0-2.79-1.1-5.43-3.86-7.46zm-8.47 15.15a7.58 7.58 0 01-4.05-1.15l-.29-.17-5.27 1.4 1.4-5.26-.19-.3a7.54 7.54 0 1110.4 10.39z" />
      <path d="M16.24 14.73c-.26-.13-1.53-.75-1.77-.84s-.41-.13-.58.13-.66.83-.81 1-.3.2-.56.07a7.4 7.4 0 01-2.18-1.35 8.2 8.2 0 01-1.53-1.9c-.16-.28 0-.43.12-.56.12-.12.26-.3.38-.45a.33.33 0 01.05-.06c.07-.06.09-.1.14-.17a.67.67 0 00.1-.19.28.28 0 000-.3c0-.06-.58-1.41-.8-1.95s-.42-.44-.58-.44-.43 0-.66 0a1.33 1.33 0 00-.72.35 3.05 3.05 0 00-1 2.44 4.34 4.34 0 001.42 2.72 7.74 7.74 0 004.43 3.28 3.52 3.52 0 001.47.15 3.1 3.1 0 001.88-1.3 3 3 0 00.21-1.31c0-.19-.13-.3-.27-.38z" />
    </svg>
    Chat with us on WhatsApp
  </a>

  <footer>
    &copy; 2025 Joseck Premier Services. All rights reserved.
  </footer>
</body>
</html>
