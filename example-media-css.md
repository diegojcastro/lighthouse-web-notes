/* Mobile Styles */
.main {
  font-weight: 700;
  font-size: 30px;
  text-align: center;
}

.section {
  line-height: 300px;
}

.menu {
  background-color: #ac1d1c;
  line-height: 80px;
  padding: 0px 40px;
}

.tagline {
  display: none;
}

.hero {
  background-color: #b2d6ff;
}

.sign-up {
  background-color: #d6e9fe;
  line-height: 300px;
}

.content {
  background-color: #c0ffee;
  height: 600px;
}

.feature {
  background-color: #f5cf8e;
}

.footer {
  color: #f0f0f0;
  background-color: #333333;
}

/* Tablet Styles */
@media only screen and (min-width: 768px) {
  .feature {
    width: 33.3%;
    line-height: 600px;
  }

  .content {
    width: 66.7%;
    float: right
  }

  .footer {
    clear: right;
  }
}

/* Desktop styles */
@media only screen and (min-width: 1024px) {
  .hero {
    width: 33.3%;
    float: left;
  }

  .feature {
    line-height: 300px;
  }

  .menu {
    background-color: #111111;
    color: #f0f0f0;
    text-align: left;
  }

  .tagline {
    display: inline;
    font-style: italic;
    font-weight: normal;
    font-size: 12px;
    color: tomato;
    float: right;
  }

  .main {
    max-width: 1024px;
    font-size: 16px;
    margin: 0 auto;
  }
}
