# Strimo

Strimo is a browser-based live broadcasting studio designed to simplify the streaming process. Developed with ease of use in mind, Strimo enables individuals and organizations to broadcast live events with professional-grade quality using simple equipment like smartphones.

## Background

The idea for Strimo was born out of necessity. As demands on local event streaming grew, we sought to create a solution that allowed people to stream events independently, without the complexities and high costs traditionally associated with multi-camera live broadcasting.

Following an intensive ski event production, which showcased the potential of using phones over expensive equipment, we recognized the need for a tool that made live streaming accessible, cost-effective, and enjoyable.

## The Company

Two months after the ski event, a company was born with a mission to revolutionize live streaming. Leveraging the power of WebRTC for reliable and stable streams, and features like WebRTC jitter buffer, Strimo aims to stand at the forefront of streaming technology.

## Product Architecture

Strimo's architecture is composed of three main components:

1. **Back-end:**
   - Handles RTMP streaming to destinations.
   - Manages authentication and permissions.
   - Maintains state storage and other core functionalities.

2. **Strimo Core:**
   - Acts as a bridge between back-end services and front-end logic.
   - Scalability and modularity.
   - Composed of three main pillars:
     - **Input Manager:** Manages the import of media sources using webRTC.
     - **Scene Manager:** Allows users to manipulate media with effects and transitions.
     - **Output Manager:** Handles the output of media to streaming platforms like Twitch and YouTube.

3. **Front-end:**
   - The user interface of the studio, which is still in the design phase.
   - The front-end is designed to be dynamic and flexible, with constant redesign iterations.

## Payment

- **Free Version:** Unlimited streaming using WHIP protocol and up to 10 hours per month to custom RTMP destinations.
- **Paid Version:** Offers extensive streaming to RTMP destinations and additional premium features.

## Technology

Strimo is built using Svelte for both the core system and the front-end to ensure a reactive and efficient user experience.

## Future Plans

- A focus on acquiring a wide user base with the free version, providing an easy transition to the paid model.
- Continuous iteration of the studio's design to enhance user experience and meet evolving user needs.

## Contribution

Interested in contributing to Strimo or have questions? Feel free to reach out or submit an issue/pull request to our repository.

## Contact

For more information on Strimo, please visit our [website](http://strimo.no).
