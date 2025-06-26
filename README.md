# WiFi Captive Portal
A lightweight Node.js-based WiFi Captive Portal that serves a login/landing page to users connected to an open WiFi network.
Ideal for public access points where you want to control access or display a message before letting users browse the internet.


## 🌐 Project Overview
This project uses Node.js and Express to serve a simple HTML page (`index.html`) to users who connect to the WiFi network. It's designed to work with router-side tools like `iptables` and `dnsmasq` to intercept traffic and redirect users to this portal.



## 📁 File Structure
wifi-captive-portal/
├── index.html
├── server.js 
├── package.json 
├── .gitignore
└── README.md

Key features:
- Network access control via a web interface
- Optional user login or payment integration
- Responsive frontend UI for mobile and desktop
- Backend logic for session tracking and authentication


## 🚀 Features

- Custom HTML/CSS landing page
- Flask (or Node.js) backend for authentication/session handling
- IP/MAC address-based session validation
- Integration with `iptables`, `dnsmasq`, and `hostapd` for Linux-based routers
- Logging of user sessions and access history
