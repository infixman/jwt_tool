# JWT Tool

A pure front-end web tool for working with JSON Web Tokens (JWTs). Built with HTML, CSS, and JavaScript using `jsrsasign` (v11.1.0). Hosted on GitHub Pages.

**[Live Demo](https://infixman.github.io/jwt_tool/)**

## Features

- Decode JWTs to view Header and Payload.
- Encode JWTs (HS256) from a payload and secret.
- Convert input to/from Base64.

## Usage

Open `index.html` in a browser or visit the [live demo](https://infixman.github.io/jwt_tool/). Paste a JWT to decode, or input a payload and secret to encode. Use Base64 buttons to convert input.

**Note**: Avoid using production JWTs, as operations are client-side.

## License

MIT License. See [LICENSE](LICENSE). `jsrsasign` is also MIT-licensed.