<p align="center">
  <img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Empress CRM logo" height="60" />
  <p align="center">
    An innovative, open-source CRM solution designed to amplify your sales performance.
    <br />
    <a href="https://grow.empress.eco/">Explore the Docs</a>
    ·
    <a href="https://github.com/empress-eco/crm/issues">Report Bug</a>
    ·
    <a href="https://github.com/empress-eco/crm/issues">Request Feature</a>
  </p>
</p>

## About The Project

### 📖 Overview
Empress CRM is a cutting-edge, open-source customer relationship management (CRM) tool crafted for businesses seeking to elevate their sales operations. This solution simplifies lead management, deal tracking, and sales analytics, empowering you to make data-driven decisions that boost your sales performance.

### 🌟 Key Features
- **Effective Lead Management:** Keep tabs on potential customers or clients for your business.
- **Deal Tracking:** Stay ahead of your deals and never miss an opportunity.
- **Sales Analytics:** Harness your sales data for informed decision-making.
- **User-friendly Interface:** Navigate through Empress CRM with ease using our intuitive UI.

## Technical Stack and Setup Instructions

### Prerequisites
This application currently depends on the `develop` branch of Empress. You need to set up Empress-bench by following this [guide](https://Empressframework.com/docs/v14/user/en/installation).

### Installation
1. Clone the repository using: `git clone https://github.com/empress-eco/crm.git`
2. Start Empress-bench by running `bench start` in the Empress-bench directory and keep it running.
3. Open a new terminal session and navigate into the `Empress-bench` directory.
4. Execute the following commands:
    ```sh
    bench new-site crm.test
    bench get-app crm
    bench --site crm.test install-app crm
    bench --site crm.test add-to-hosts
    bench --site crm.test browse --user Administrator
    ```
5. Open a new terminal session, navigate into `Empress-bench/apps/crm`, and run the following commands:
    ```sh
    yarn
    yarn dev
    ```
6. Access the site on the vite dev server at `http://crm.test:8080`.

## Usage
After installation, begin using Empress CRM to manage your leads, track deals, and analyze your sales data. Refer to the screenshots in our [Github Repository](https://github.com/empress-eco/crm) for a visual guide on how to navigate the application.

## Contribution Guidelines
While we don't currently expect contributions, we always welcome bug reports, feature requests, and suggestions. Please feel free to open an issue if you encounter any bugs or have any feature requests or suggestions. We appreciate your input and contribution to improving Empress CRM!

## Support
For support, visit our [website](https://grow.empress.eco/).

## License and Acknowledgements
### License
This project and your contributions are licensed under the MIT License.

### Acknowledgements
A special shout-out to the Empress Community, the brains behind the critical tools that power this project. Their innovation and dedication have been instrumental in building the foundations and functionalities we rely on. We are profoundly grateful for their pioneering work and ongoing support.