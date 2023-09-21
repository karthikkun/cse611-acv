## **Technical Specifications**


## User Experience
  1. ## Wireframes

**Tool Used:** Figma

Figma has been chosen as the tool for wireframing for this project. It provides a seamless, collaborative interface which facilitates real-time collaboration among designers and stakeholders. Being browser-based, Figma ensures easy accessibility across different platforms without necessitating any software installation.

**Link to Wireframes:** 
[ACV Auctions Design on Figma](https://www.figma.com/file/5Mtr0Qc8Zp6L1sZxzj0lsx/ACV-Auctions-Design?type=design&node-id=0-1&mode=design&t=Sn1hM4I8FrDCLNFB-0)

**Description:** 
The Figma link provided above showcases the wireframes created for the ACV Auctions Design. These wireframes present a visual representation of the anticipated user interface, detailing the layout, user interactions, and overall user experience. Acting as a blueprint, they offer developers and stakeholders a clear understanding of the expected user flow and design elements.

 2. ## User Flow or User Journey Scheme

To Do

### User Interface Development - 
1. ## React Native

**Why React Native for ACVAuctions?**

- **Cross-Platform:** Develop for Android and iOS simultaneously, ensuring consistency.
- **Performance:** Near-native speed, with options to use native modules for optimization.
- **Community:** Vast support from developers worldwide, ensuring updates and quick fixes.
- **Efficiency:** Hot-reload feature speeds up the development process.
- **Flexibility:** Modular design for quick upgrades and easy integration with other apps.

React Native was chosen for ACVAuctions due to its capability for efficient, cross-platform development and its strong community support. It aligns with our goals to provide a consistent and high-performance app experience.

2. ## Redux

**Why Redux for ACVAuctions?**

- **Predictability:** Redux enforces a unidirectional data flow, making state changes predictable.
- **Maintainability:** It encourages code modularity, making the codebase more maintainable.
- **Server Rendering:** Redux is conducive to server-side rendering for faster initial page loads.
- **Developer Tools:** The Redux DevTools provide powerful features for debugging and state tracking.
- **Community:** Extensive community support provides libraries, middlewares, and solutions to common issues.

Redux was chosen for ACVAuctions due to its robustness in state management and developer-friendly tools. It ensures a scalable and maintainable approach to handle the app's state.

  3. ## Development Language - TypeScript

**Why TypeScript for ACVAuctions?**

- **Static Typing:** Offers type checking during compile time, reducing runtime errors.
- **Enhanced Readability:** Types and interfaces improve code readability and maintainability.
- **Robust Tooling:** Intelligent code suggestions, refactoring, and improved navigation with IDEs.
- **Scalability:** Well-suited for large codebases ensuring better maintainability.
- **ESNext Features:** Allows the use of the latest JavaScript features while ensuring backward compatibility.

TypeScript was chosen for ACVAuctions due to its powerful static typing and developer tooling. It ensures a safer, more maintainable, and scalable codebase for the application.

  4. ## UI Framework - Material-UI

**Why Material-UI for ACVAuctions?**

- **Consistency:** Based on Google's Material Design, ensuring a consistent and modern UI.
- **Component Library:** Rich set of pre-designed components accelerates development.
- **Customizable:** Theming and styling solutions adapt to brand-specific designs.
- **Responsiveness:** Built-in responsive design techniques ensure great user experience across devices.
- **Community:** Strong community support, leading to regular updates and a plethora of resources.

Material-UI was selected for ACVAuctions to facilitate a consistent, efficient, and customizable UI development. It aligns with our aim to offer a polished and


### Backend Development: Firebase

**Why Firebase for ACVAuctions?**
- **Real-time Database**: Ensures real-time synchronization of data across user devices.
- **Scalability**: Provides auto-scaling to cater to growing user numbers without any manual adjustments.
- **Authentication**: Supports various authentication methods with built-in services.
- **Serverless Functions**: Uses Cloud Functions to facilitate server-side logic without needing server management.
- **Analytics & Monitoring**: Implements tools such as Firebase Analytics for in-depth insights and performance diagnostics.

> _Rationale_: Firebase has been chosen for ACVAuctions due to its comprehensive backend solutions, ensuring seamless scalability. This platform allows our team to prioritize user needs while simplifying backend complexities.


## Database (Key Value stores)

### 1 S3

**Why S3 for ACVAuctions?**
- **Image Storage for API**: Stores images that are linked when calling the damage detection API in our app.
- **Durability & Availability**: Offers unparalleled durability and availability, ensuring the stored images are reliably accessible.
- **Security**: Advanced security measures, such as ACLs and bucket policies, protect the data.

> _Rationale_: S3 is pivotal to ACVAuctions, primarily because it effectively stores images required by our damage detection API. The security and reliability of S3 ensure these images are always accessible.

### 2 Firebase

**Why Firebase for ACVAuctions?**
- **Legacy Infrastructure**: ACVAuctions' existing infrastructure is rooted in Firebase.
- **Real-time Database**: Allows for instantaneous data synchronization.
- **Scalability**: Adapts to user traffic demands seamlessly.
- **Serverless Functions**: Simplifies server-side logic with Cloud Functions.

> _Rationale_: Firebase's features mesh well with ACVAuctions' present infrastructure. Its capabilities, from real-time data synchronization to serverless functions, ensure that the application is both efficient and user-centric.

## Infrastructure

### GitHub

**Why GitHub for ACVAuctions?**
- **Team Collaboration**: Facilitates collaboration among team members, streamlining development workflows.
- **Version Control**:  [To be filled in later]
- **Branching Strategy**: [To be filled in later]

> _Rationale_: GitHub is an essential tool for ACVAuctions. Its collaborative features allow our team to work in sync, and its version control mechanisms ensure the consistency and integrity of our codebase.

### AWS

**Why AWS for ACVAuctions?**
- **S3 Storage**: AWS's S3 service is vital for storing images linked to the damage detection API in our app.
- **Scalability**: AWS services, especially S3, scale effortlessly based on our data storage needs.
- **Reliability**: AWS offers a stable and reliable infrastructure platform.

> _Rationale_: AWS, particularly its S3 service, provides ACVAuctions with the necessary infrastructure to handle our image storage needs for the damage detection API. Its scalability and reliability make it an optimal choice for our evolving requirements.




