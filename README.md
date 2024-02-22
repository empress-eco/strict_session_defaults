<div align="center">
  <img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Project Logo">
  <p align="center">
  Empowering developers with robust and streamlined session management.
  <br />
  <a href="https://grow.empress.eco/">Explore the Docs</a>
  ·
  <a href="https://github.com/empress-eco/strict_session_defaults/issues/new">Report Bug</a>
  ·
  <a href="https://github.com/empress-eco/strict_session_defaults/issues/new">Request Feature</a>
  </p>
</div>

## About The Project

### 📖 Overview
Strict Session Defaults is a compact and efficient plugin designed to enhance session management for developers and administrators. It simplifies and reinforces session defaults, ensuring a secure and smooth user experience.

### 🌟 Key Features
- Quick and easy installation
- Customizable session settings
- Reliable enforcement of session defaults

## Getting Started

### Prerequisites
- Empress >= v13.0.0

### Installation
Follow these straightforward steps to get Strict Session Defaults up and running:

1. Navigate to your bench directory:

   ```sh
   cd ~/Empress-bench
   ```

2. Clone the plugin from GitHub:

   ```sh
   git clone https://github.com/empress-eco/strict_session_defaults.git
   ```

3. Build the plugin:

   ```sh
   bench build --app strict_session_defaults
   ```

4. Install the plugin on your desired site:

   ```sh
   bench --site [sitename] install-app strict_session_defaults
   ```

## Usage
After installation, you can easily manage your session settings:

1. Navigate to `Strict Session Defaults Settings`
2. Enable the feature by checking the `Is Enabled` box
3. Select your preferred `Roles Condition`
4. Add roles that the condition will apply to
5. Similarly, manage the `Users Condition` and `Users`

## Contributing
We welcome your contributions! Here's how you can contribute:

- Fork the Project
- Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
- Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
- Push to the Branch (`git push origin feature/AmazingFeature`)
- Open a Pull Request

## License and Acknowledgements

### License
This project is licensed under the MIT License. All contributions made to this project are also under the MIT License.

### Acknowledgements
We extend our heartfelt gratitude to the Empress Community for their pioneering work and enduring support that has been instrumental in the development of this project. Our sincere thanks to our contributors and our supportive community for their constant feedback and assistance.