# AliveFrame AR Experience (PWA)

This project is an Augmented Reality (AR) web application built with A-Frame and MindAR, designed to run as a Progressive Web App (PWA). It allows users to scan a poster and view an AR video overlay, with a modern, mobile-friendly interface.

## Features
- Augmented Reality experience using MindAR and A-Frame
- Progressive Web App (PWA) support: installable on mobile and desktop
- Custom install notification bar for easy app installation
- Service worker for offline support
- Responsive and touch-friendly UI
- Poster tracking and video overlay

## How to Run
1. **Clone or download this repository.**
2. **Serve the project with a local web server.**
	- Python 3: `python -m http.server`
	- Node.js: `npx serve`
	- Or use any static server of your choice.
3. **Open `http://localhost:8000` (or the port your server uses) in your browser.**
4. **Scan the target poster with your device's camera.**

## PWA Installation
- When visiting the site, a notification bar will appear at the top with an Install button.
- Click Install to add the app to your device's home screen.
- The install bar will not appear if the app is already installed.

## Project Structure
- `index.html` – Main application file
- `manifest.json` – PWA manifest
- `service-worker.js` – Service worker for offline support
- `logo.jpg` – App icon
- `pk.jpg` – Poster image for AR tracking
- `video.mp4` – Video overlay for AR
- `target.mind` – MindAR target file

## Dependencies
- [A-Frame](https://aframe.io/)
- [MindAR](https://hiukim.github.io/mind-ar-js-doc/)
- [FontAwesome](https://fontawesome.com/)

## Customization
- Replace `logo.jpg`, `pk.jpg`, and `video.mp4` with your own assets as needed.
- Update `manifest.json` for your app's name, icons, and theme color.

## License
This project is for educational and demonstration purposes.
# AR_experience