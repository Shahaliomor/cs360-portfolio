# cs360-portfolio

The mobile application I developed, SAO Weight Tracking, was designed to help users record their daily weight, set a target, and receive alerts when they reach their goal. This app addresses the need for a simple, private, and reliable weight tracking solution without requiring accounts or internet connectivity. By focusing on local data storage, it ensures user privacy while keeping the experience lightweight and accessible.

To meet these user needs, the app includes key screens such as a home/history list for tracking entries, a data entry screen for adding or editing weight, and a goal setting interface with a progress indicator. Once a user’s target is reached, the app delivers a high-priority notification, and optionally an SMS alert, to reinforce motivation. These design choices emphasized clarity, accessibility, and minimal friction, which made the UI user-centered and successful.

In coding the app, I used an iterative, modular approach. I broke development into small tasks—CRUD operations for entries, goal logic, notification setup, and SMS integration. I followed best practices such as consistent naming, commenting code for readability, and testing features incrementally. These strategies can be applied to future projects to ensure adaptability and maintainability.

Testing was essential. I validated all CRUD operations with SQLite, confirmed goal tracking, and checked notification flows. I also tested denied-permission paths (e.g., when SMS or notifications are blocked) to ensure the app still functioned. This process confirmed robustness and revealed areas where validation and user prompts improved usability.

One challenge I faced was ensuring that SMS permissions behaved gracefully across different Android versions. To overcome this, I researched Android documentation and implemented a fallback that opens the default SMS app with a prefilled message if permissions are denied. This innovation allowed the app to remain functional while respecting user privacy and modern permission models.

The component I am most proud of is the goal-reached alert system. It demonstrated my ability to integrate Android services (notifications and SMS), manage permissions responsibly, and tie them into the core functionality of the app. This feature highlights my skills in combining design, coding, and testing to deliver a polished user experience.

Overall, this project reflects my ability to create a functional mobile application that applies both mobile development best practices and user-centered design principles. It also showcases my growth in solving challenges with innovative, privacy-conscious solutions.
