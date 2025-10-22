<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Student News & Updates</title>
<style>
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background: linear-gradient(135deg, #74ebd5, #ACB6E5);
    margin: 0;
    padding: 20px;
    color: #333;
  }
  header {
    text-align: center;
    padding: 40px 0 20px 0;
    color: #4a148c;
    font-size: 2.8rem;
    font-weight: 700;
    animation: fadeInDown 1.2s ease forwards;
  }
  @keyframes fadeInDown {
    from {
      opacity: 0;
      transform: translateY(-50px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }
  .news-container {
    max-width: 900px;
    margin: auto;
  }
  .news-item {
    background: white;
    border-radius: 15px;
    box-shadow: 0 6px 15px rgba(74,20,140,0.2);
    margin-bottom: 30px;
    overflow: hidden;
    transform: translateY(50px);
    opacity: 0;
    animation: slideUpFade 1s ease forwards;
  }
  .news-item:nth-child(1) {
    animation-delay: 0.2s;
  }
  .news-item:nth-child(2) {
    animation-delay: 0.4s;
  }
  .news-item:nth-child(3) {
    animation-delay: 0.6s;
  }
  @keyframes slideUpFade {
    to {
      transform: translateY(0);
      opacity: 1;
    }
  }
  .news-header {
    background: linear-gradient(135deg, #6a11cb, #2575fc);
    padding: 15px 25px;
    color: white;
    font-weight: 700;
    font-size: 1.4rem;
  }
  .news-body {
    padding: 20px 25px;
    font-size: 1.1rem;
    line-height: 1.6;
    color: #444;
  }
  .news-footer {
    background: #f3f3f3;
    padding: 15px 25px;
    font-size: 0.9rem;
    color: #777;
    font-style: italic;
  }
  a.read-more {
    display: inline-block;
    margin-top: 10px;
    font-weight: 600;
    color: #6a11cb;
    text-decoration: none;
    transition: color 0.3s ease;
  }
  a.read-more:hover {
    color: #2575fc;
    text-decoration: underline;
  }
</style>
</head>
<body>

<header>Student News & Important Updates</header>

<div class="news-container">
  <article class="news-item">
    <div class="news-header">Campus Reopens with New Safety Protocols</div>
    <div class="news-body">
      The university campus will reopen on November 1st, 2025, with enhanced safety measures including mandatory masks in all indoor areas and frequent sanitization stations. Stay tuned for detailed guidelines.
      <br /><a href="#" class="read-more">Read More</a>
    </div>
    <div class="news-footer">Posted on October 20, 2025</div>
  </article>

  <article class="news-item">
    <div class="news-header">Internship Opportunities Openings for Fall 2025</div>
    <div class="news-body">
      Exciting internship opportunities from top tech and finance companies are now available. Visit the career portal to apply before the deadline on November 15th.
      <br /><a href="#" class="read-more">Read More</a>
    </div>
    <div class="news-footer">Posted on October 18, 2025</div>
  </article>

  <article class="news-item">
    <div class="news-header">New Online Workshops for Skill Development</div>
    <div class="news-body">
      Sign up for free online workshops covering topics like data science, creative writing, and digital marketing. Sessions start from November 5th. Seats are limited.
      <br /><a href="#" class="read-more">Read More</a>
    </div>
    <div class="news-footer">Posted on October 15, 2025</div>
  </article>
</div>

</body>
</html>
