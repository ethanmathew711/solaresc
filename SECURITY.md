<security.html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Security Policy | Solar Eclipse</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, Helvetica, sans-serif;
      min-height: 100vh;
      color: #fff;
      background:
        radial-gradient(circle at top, #243b70 0%, #080b16 45%, #020308 100%);
      padding: 40px 20px;
    }

    .container {
      width: min(950px, 100%);
      margin: auto;
    }

    .back {
      display: inline-block;
      margin-bottom: 25px;
      color: #8fc7ff;
      text-decoration: none;
      font-weight: bold;
    }

    .back:hover {
      color: #fff;
    }

    .card {
      background: rgba(15, 20, 40, 0.72);
      border: 1px solid rgba(120, 180, 255, 0.25);
      border-radius: 24px;
      padding: 45px;
      backdrop-filter: blur(18px);
      box-shadow: 0 25px 80px rgba(0, 0, 0, 0.5);
    }

    .badge {
      display: inline-block;
      padding: 8px 14px;
      border-radius: 999px;
      background: rgba(80, 160, 255, 0.15);
      border: 1px solid rgba(100, 180, 255, 0.35);
      color: #8fc7ff;
      font-size: 13px;
      font-weight: bold;
      letter-spacing: 1px;
      margin-bottom: 18px;
    }

    h1 {
      font-size: clamp(36px, 7vw, 64px);
      margin-bottom: 15px;
      background: linear-gradient(90deg, #fff, #7fc4ff);
      -webkit-background-clip: text;
      color: transparent;
    }

    .intro {
      color: #b9c5dc;
      font-size: 17px;
      line-height: 1.7;
      margin-bottom: 40px;
    }

    section {
      margin-top: 40px;
    }

    h2 {
      font-size: 25px;
      margin-bottom: 15px;
      color: #8fc7ff;
    }

    p,
    li {
      color: #c7d0e2;
      line-height: 1.75;
    }

    ul {
      padding-left: 25px;
      margin-top: 12px;
    }

    li {
      margin-bottom: 8px;
    }

    .table-wrapper {
      overflow-x: auto;
      margin-top: 20px;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      min-width: 500px;
      overflow: hidden;
      border-radius: 12px;
    }

    th,
    td {
      padding: 16px;
      text-align: left;
      border-bottom: 1px solid rgba(255,255,255,0.1);
    }

    th {
      background: rgba(100, 170, 255, 0.12);
      color: #fff;
    }

    td {
      background: rgba(255,255,255,0.025);
    }

    .supported {
      color: #72ffb0;
      font-weight: bold;
    }

    .unsupported {
      color: #ff7f8a;
      font-weight: bold;
    }

    .notice {
      margin-top: 20px;
      padding: 20px;
      border-left: 4px solid #65b7ff;
      background: rgba(70, 150, 255, 0.08);
      border-radius: 10px;
    }

    .footer {
      text-align: center;
      margin-top: 35px;
      color: #77849e;
      font-size: 14px;
    }

    @media (max-width: 600px) {
      body {
        padding: 20px 12px;
      }

      .card {
        padding: 28px 20px;
        border-radius: 18px;
      }

      h1 {
        font-size: 42px;
      }
    }
  </style>
</head>

<body>

  <div class="container">

    <a href="index.html" class="back">← Back to Solar Eclipse</a>

    <div class="card">

      <span class="badge">SECURITY CENTER</span>

      <h1>Security Policy</h1>

      <p class="intro">
        Your security matters. This page explains how security
        vulnerabilities in the Solar Eclipse project can be reported
        and how they will be handled.
      </p>

      <section>
        <h2>Supported Versions</h2>

        <p>
          The latest version of the Solar Eclipse project is currently
          supported with security updates.
        </p>

        <div class="table-wrapper">
          <table>
            <thead>
              <tr>
                <th>Version</th>
                <th>Supported</th>
              </tr>
            </thead>

            <tbody>
              <tr>
                <td>Latest</td>
                <td class="supported">✓ Supported</td>
              </tr>

              <tr>
                <td>Older versions</td>
                <td class="unsupported">✕ Not supported</td>
              </tr>
            </tbody>
          </table>
        </div>
      </section>

      <section>
        <h2>Reporting a Vulnerability</h2>

        <p>
          If you discover a security vulnerability, please report it
          privately rather than publicly posting information about it.
        </p>

        <div class="notice">
          Please include as much useful information as possible so the
          issue can be investigated quickly.
        </div>

        <ul>
          <li>A clear description of the security problem</li>
          <li>The affected page or feature</li>
          <li>Steps needed to reproduce the issue</li>
          <li>Relevant screenshots or error messages</li>
          <li>The potential impact of the vulnerability</li>
        </ul>
      </section>

      <section>
        <h2>What to Expect</h2>

        <p>
          Security reports will be reviewed and investigated. If a
          vulnerability is confirmed, an appropriate fix will be
          developed and the project will be updated when possible.
        </p>

        <br>

        <p>
          If a report is not considered a security vulnerability,
          an explanation may be provided and the issue can be directed
          to the appropriate reporting channel.
        </p>
      </section>

      <section>
        <h2>Thank You</h2>

        <p>
          Thank you for helping make the Solar Eclipse project safer
          for everyone.
        </p>
      </section>

    </div>

    <div class="footer">
      © 2026 Solar Eclipse • Security Center
    </div>

  </div>

</body>
</html>
