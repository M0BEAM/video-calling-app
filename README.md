
# Video Calling App using Stream Video React SDK

This project demonstrates how to implement a video calling app using the `@stream-io/video-react-sdk`. It allows users to join video calls, display participant layouts, and includes basic call controls.

## Features

- Video call functionality using Stream Video React SDK
- Displays participants with a bottom-aligned participant bar
- Basic call controls (e.g., mute, leave call, etc.)
- Fully customizable UI layout

## Prerequisites

Before starting, ensure you have the following:

- A valid [Stream API Key](https://getstream.io/)
- A user token generated for the video calling session
- A valid `userId` and `callId` for your session

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/video-calling-app.git
cd video-calling-app
```

### 2. Install dependencies

Run the following command to install the required dependencies:

```bash
npm install
```

### 3. Configuration

You will need to provide your Stream API credentials and user details in the code. Open the main file (`App.tsx`) and update the following values:

```typescript
const apiKey = 'Your_Api_Key';
const token = 'YourToken';
const userId = 'Your_userId';
const callId = 'Your_callId';
```

### 4. Run the app

Once the credentials are set up, run the app using:

```bash
npm run dev
```

This will start the development server. Open your browser and go to [http://localhost:3000](http://localhost:3000) to see the app in action.

## Project Structure

- `App.tsx`: The main entry point that sets up the video client and call.
- `MyUILayout.tsx`: Custom UI layout that displays participants and controls.

## Dependencies

- `@stream-io/video-react-sdk`: Stream's React SDK for building video chat applications.
- `react`: JavaScript library for building user interfaces.
- `vite`: Fast build tool and development server.

## Screenshots

You can add screenshots of the app here to give users a preview of the interface.

## License

This project is licensed under the MIT License.
