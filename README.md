# UserAuthSystem

## 🚀 Modern Account System

An elegant, responsive, and feature-rich account management system built with HTML, CSS, and JavaScript. This implementation provides a seamless user experience while maintaining security with modern authentication practices.

### ✨ Key Features

- **Clean, Modern UI/UX Design**: Professional appearance with smooth animations and transitions
- **Responsive Layout**: Works perfectly on mobile, tablet, and desktop devices
- **Dark/Light Mode**: Automatically adapts to user's system preferences
- **Complete Account Lifecycle**:
  - User login with secure credential handling
  - New account registration with validation
  - Password recovery workflow
- **Security Features**:
  - Password visibility toggle
  - Client-side input validation
  - PASETO data encryption
- **Smooth Interactions**:
  - Tab-based navigation between forms
  - Loading indicators during API operations
  - using i18n
  - Clear success/error feedback

## 📋 Usage Instructions

### Setup

Please obfuscate all javascript files before use

1. **Front-End**:
   Download "front-end.zip" and Unzip
   deploy it to a proxy, such as nginx
   Please change the api in config.json to the correct backend link

2. **Back-end**
   Download "Back-end.zip" and Unzip
   deplot it to a JAVA 21
   Please change the KEY & API in _config.json
   

## 🛡️ Disclaimer

This account system is provided as a front-end template and demonstration only. Important considerations:

1. **Security**: 
   - The Base64 encryption used in this demo is NOT secure for production environments.
   - In a production environment, implement proper HTTPS, secure token-based authentication, and server-side validation.
   - The CAPTCHA implementation is client-side only and should be supplemented with server-side verification in production.

2. **Data Protection**:
   - This template does not include data protection measures required by regulations like GDPR or CCPA.
   - Implement appropriate data protection policies and mechanisms before collecting user data.

3. **API Implementation**:
   - The system assumes specific API endpoints and responses as detailed above.
   - Server-side implementation of these APIs is not included.

4. **No Warranty**:
   - This code is provided "as is" without warranty of any kind, express or implied.
   - The authors are not responsible for any issues arising from the use of this code.

## 📝 License

This project is released under the MIT License. See the LICENSE file for details.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check issues page.

---

© 2025 Onmi-Tech. All rights reserved.
