:root {

  /* Farben */

  --primary: #c42cb8;

  --primary-dark: #6a1d8f;

  --accent: #f2d43d;

  --background: #fff9f2;

  --surface: #ffffff;

  --text: #1d1d1f;

  --text-light: #666666;

  /* Layout */

  --max-width: 1200px;

  --radius: 18px;

  --shadow: 0 10px 30px rgba(0, 0, 0, .08);

  /* Abstände */

  --space-xs: .5rem;

  --space-sm: 1rem;

  --space-md: 2rem;

  --space-lg: 4rem;

  --space-xl: 8rem;

}

* {

  box-sizing: border-box;

}

html {

  scroll-behavior: smooth;

}

body {

  margin: 0;

  min-height: 100vh;

  background: var(--background);

  color: var(--text);

  font-family:

    Inter,

    system-ui,

    -apple-system,

    BlinkMacSystemFont,

    "Segoe UI",

    sans-serif;

  line-height: 1.6;

}