# JOKE-WEB

---

Web application where you can find the best jokes for programmers. Here you can:

- Create jokes
- Use AI to generate jokes
- Edit jokes
- Play jokes
- Generate and download audio to share
- Generate and download an image to share
- Delete jokes
- Rate the joke as good or bad

---

## Built with Vue 3 and Vite

This application is developed using Vue 3, the progressive JavaScript framework for building user interfaces. Vue 3 brings enhanced performance, improved composition API, and better TypeScript integration, making our application more efficient and developer-friendly.

We use Vite as our build tool, which offers a fast development environment with features such as hot module replacement (HMR) and efficient bundling for production. Vite's design leverages modern JavaScript features and aims to provide a leaner and faster development experience.

### Getting Started with Development

To run this project locally, follow these steps:

1. **Clone the repository**:

   ```
   git clone [repository URL]
   ```

2. **Navigate to the project directory**:

   ```
   cd [project directory]
   ```

3. **Install dependencies**:

   ```
   npm install
   ```

4. **Run the development server**:

   ```
   npm run dev
   ```

   This command starts the local development server using Vite. Open [http://localhost:3000](http://localhost:3000) to view the application in your browser.

For more detailed documentation on Vue 3 and Vite, visit their respective official documentation:

- [Vue 3 Documentation](https://v3.vuejs.org/)
- [Vite Documentation](https://vitejs.dev/)

---

### Amplify

This application is hosted on Amplify. To get started with the process, you can follow these instructions:

1. **Set up your environment**: Ensure you have Node.js installed on your machine. Amplify supports Node.js versions 12 and above.

2. **Install the Amplify CLI**: Open your terminal (command prompt or PowerShell on Windows) and install the Amplify Command Line Interface (CLI) by running `npm install -g @aws-amplify/cli`.

3. **Configure Amplify**: Once the installation is complete, configure Amplify by running `amplify configure`. This command will guide you through the initial setup, including the creation of an AWS account if you do not already have one.

4. **Initialize Amplify in your project**: Navigate to the root directory of your project in the terminal and run `amplify init`. This command initializes a new Amplify project and you will be prompted to answer questions about your project's configuration.

5. **Add hosting**: To add hosting to your Amplify project, run `amplify add hosting`. This will allow you to host your web application on AWS.

6. **Deploy your application**: Finally, deploy your application by running `amplify publish`. This command builds your web application and deploys it to AWS Amplify Hosting.

For more detailed instructions and additional options, please refer to the [official Amplify documentation](https://docs.amplify.aws/vue/start/getting-started/introduction/).

---

## Libraries and Assets

In this project, we utilize a range of libraries and assets to enhance the user experience and functionality of our web application:

- **Icons**: From Iconfinder. We use various icons to improve the UI's visual appeal and user navigation.
- **CSS Framework**: Tailwind CSS. This utility-first CSS framework is used for designing custom user interfaces with speed and efficiency.
- **Charts**: Chart.js and vue-chart-3. These libraries are employed to render interactive and responsive charts for a better representation of data.
- **Toast Notifications**: vue3-toastify. This Vue 3 compatible library provides an easy way to display toast notifications, enhancing the feedback experience for actions taken by users.
- **Analytics**: Firebase Analytics. We leverage Firebase Analytics to understand user behavior, app usage patterns, and improve app performance based on collected data.

---


# JOKE BG

---

## Python Backend for Joke Web Application

This section of the project is dedicated to the Python-based backend, which serves as the foundation for our web application focused on jokes. The backend is designed to be deployed on AWS Lambda, offering a serverless architecture that scales automatically with the application's usage, ensuring efficient performance and cost management.

### Features:

- **Lambda Functions**: You'll find code templates to create your own AWS Lambda functions, designed to handle various backend tasks such as fetching, creating, editing, and deleting jokes.
- **Jokes Database**: Includes the base file for jokes storage. This can be integrated with AWS DynamoDB or any other database service of your choice, to manage joke entries dynamically.
- **Image and Audio Generation**: Sample codes are provided to demonstrate how to generate images and audios for jokes. These can be utilized to enhance the user experience by allowing users to download or share jokes in multimedia formats.

### Getting Started:

1. **Clone the Repository**:
   Ensure you have Git installed on your machine. Clone the repository to your local machine using:
   ```
   git clone [repository URL]
   ```
2. **Set Up a Virtual Environment**:
   It's recommended to create a virtual environment for Python projects. Use the following command:
   ```
   python3 -m venv venv
   ```
   Activate the virtual environment:
   - On Windows: `venv\Scripts\activate`
   - On Unix or MacOS: `source venv/bin/activate`

3. **Install Dependencies**:
   Install all necessary Python packages for the project:
   ```
   pip install -r requirements.txt
   ```

4. **Configure AWS CLI**:
   Make sure you have the AWS CLI installed and configured with your AWS account. You can configure it by running:
   ```
   aws configure
   ```
   This will prompt you to enter your AWS Access Key ID, Secret Access Key, region, and output format.

5. **Deploy to AWS Lambda**:
   Use the provided scripts or AWS SAM (Serverless Application Model) to deploy your Lambda functions. Check the AWS documentation for detailed instructions on deploying Lambda functions.

### Examples:

- **Creating Images**: Example code for generating joke images using Python libraries such as Pillow or OpenCV.
- **Generating Audio**: Sample scripts to convert text to audio using AWS Polly or similar TTS (Text-to-Speech) services.

For detailed examples and further instructions on how to use and deploy these features, refer to the provided documentation and comments within the codebase.

---