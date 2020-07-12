<head>
  <meta charset="utf-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  {%- seo -%}

  <!-- Styles -->
  <link rel="stylesheet" href="/assets/css/main.css" />

  <!-- Analytics -->
  {%- if jekyll.environment == 'production' and site.google_analytics -%} 
    {%- include google-analytics.md -%} 
  {%- endif -%} 
  
  <!-- Favicons -->
  <link rel="apple-touch-icon" sizes="180x180" href="/assets/favicon/apple-touch-icon.png">
  <link rel="icon" type="image/png" sizes="32x32" href="/assets/favicon/favicon-32x32.png">
  <link rel="icon" type="image/png" sizes="16x16" href="/assets/favicon/favicon-16x16.png">
  <link rel="manifest" href="/assets/favicon/site.webmanifest">
  <link rel="mask-icon" href="/assets/favicon/safari-pinned-tab.svg" color="#5bbad5">
  <meta name="msapplication-TileColor" content="#da532c">
  <meta name="theme-color" content="#ffffff">

  <!-- Twitter Card Tags -->
  <meta name="twitter:card" content="summary" />
  <meta name="twitter:site" content="@kevando_" />
  <meta name="twitter:title" content="{{ page.twitter.title}}" />
  <meta name="twitter:description" content="{{ page.twitter.description }}" />
  <meta name="twitter:image" content="https://chaz.co/assets/images/skinner.png" />

  <!-- Facebook Preview Tags -->
  <meta property="og:url" content="https://chaz.co" />
  <meta property="og:type" content="article" />
  <meta property="og:title" content="{{ page.facebook.title}}" />
  <meta property="og:description" content="{{ page.facebook.description }}" />
  <meta property="og:image" content="/assets/images/skinner.png" />
</head>