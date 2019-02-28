# react-captcha

React component for captcha.

Note that in most cases you should consider [Google Recaptcha](https://www.google.com/recaptcha/intro/v3.html) instead of delivering custom solution.

## Feature

- [x] Canvas Image
- [x] Refresh Button
- [x] Play Button (Listen to Audio)

## Usage

[codesandbox](https://codesandbox.io/s/lrzwx9mo2l)

```
npm install --save demos-react-captcha
```

```jsx
<Captcha
  onChange={/* change handler function */}
  placeholder="Enter captcha" // optional
  length={6} // default
/>
```

## Styling

By default a style is included, but you can style it using regular css.
