# Google Bard API
[![Better Stack Badge](https://uptime.betterstack.com/status-badges/v1/monitor/t0t1.svg)](https://status.nishantapps.in/?utm_source=status_badge)
```markdown
# Express Chat Application with Google AI Generative Language

This is a simple Express application that uses the Google AI Generative Language API to generate responses to user input.

## Installation

1. Clone this repository.
2. Install the required dependencies using the following command:
   ```sh
   npm install
   ```

## Configuration

1. Set up a Google Cloud project and enable the Discuss API.
2. Obtain an API key and replace `process.env.plamkey` with your API key.
3. Set up a `.env` file and add your environment variables:
   ```env
   PORT=3000
   ```

## Usage

1. Run the application using the following command:
   ```sh
   node index.js
   ```
2. Access the application at `http://localhost:3000`.
3. Send a GET request to the root route with a `text` header to generate a response.

## API Endpoint

- **Endpoint:** `/`
- **Method:** GET
- **Headers:**
  - `text`: The user input text for generating a response.
- **Response:** JSON object containing the generated response.

## Supported Languages

```languages

auto: 'Automatic',
    af: 'Afrikaans',
    sq: 'Albanian',
    ar: 'Arabic',
    hy: 'Armenian',
    az: 'Azerbaijani',
    eu: 'Basque',
    be: 'Belarusian',
    bn: 'Bengali',
    bs: 'Bosnian',
    bg: 'Bulgarian',
    ca: 'Catalan',
    ceb: 'Cebuano',
    ny: 'Chichewa',
    'zh-cn': 'Chinese Simplified',
    'zh-tw': 'Chinese Traditional',
    co: 'Corsican',
    hr: 'Croatian',
    cs: 'Czech',
    da: 'Danish',
    nl: 'Dutch',
    en: 'English',
    eo: 'Esperanto',
    et: 'Estonian',
    tl: 'Filipino',
    fi: 'Finnish',
    fr: 'French',
    fy: 'Frisian',
    gl: 'Galician',
    ka: 'Georgian',
    de: 'German',
    el: 'Greek',
    gu: 'Gujarati',
    ht: 'Haitian Creole',
    ha: 'Hausa',
    haw: 'Hawaiian',
    iw: 'Hebrew',
    hi: 'Hindi',
    hmn: 'Hmong',
    hu: 'Hungarian',
    is: 'Icelandic',
    ig: 'Igbo',
    id: 'Indonesian',
    ga: 'Irish',
    it: 'Italian',
    ja: 'Japanese',
    jw: 'Javanese',
    kn: 'Kannada',
    kk: 'Kazakh',
    km: 'Khmer',
    ko: 'Korean',
    ku: 'Kurdish (Kurmanji)',
    ky: 'Kyrgyz',
    lo: 'Lao',
    la: 'Latin',
    lv: 'Latvian',
    lt: 'Lithuanian',
    lb: 'Luxembourgish',
    mk: 'Macedonian',
    mg: 'Malagasy',
    ms: 'Malay',
    ml: 'Malayalam',
    mt: 'Maltese',
    mi: 'Maori',
    mr: 'Marathi',
    mn: 'Mongolian',
    my: 'Myanmar (Burmese)',
    ne: 'Nepali',
    no: 'Norwegian',
    ps: 'Pashto',
    fa: 'Persian',
    pl: 'Polish',
    pt: 'Portuguese',
    ma: 'Punjabi',
    ro: 'Romanian',
    ru: 'Russian',
    sm: 'Samoan',
    gd: 'Scots Gaelic',
    sr: 'Serbian',
    st: 'Sesotho',
    sn: 'Shona',
    sd: 'Sindhi',
    si: 'Sinhala',
    sk: 'Slovak',
    sl: 'Slovenian',
    so: 'Somali',
    es: 'Spanish',
    su: 'Sudanese',
    sw: 'Swahili',
    sv: 'Swedish',
    tg: 'Tajik',
    ta: 'Tamil',
    te: 'Telugu',
    th: 'Thai',
    tr: 'Turkish',
    uk: 'Ukrainian',
    ur: 'Urdu',
    uz: 'Uzbek',
    vi: 'Vietnamese',
    cy: 'Welsh',
    xh: 'Xhosa',
    yi: 'Yiddish',
    yo: 'Yoruba',
    zu: 'Zulu',
```

## Error Handling

If an error occurs during message generation, the server will respond with a default error message.

## Dependencies

- `express`: Web application framework for Node.js.
- `@google-ai/generativelanguage`: Google AI Generative Language client library.
- `google-auth-library`: Google Cloud authentication library.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
