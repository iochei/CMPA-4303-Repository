# Project 02 Reflection: SecuriKey IAM Access Portal

### Decisions
The most critical decision I made during this project was pivoting the visual layout toward a high-contrast card-based structure rather than relying on standard cluttered form inputs. In enterprise identity and access management, clarity is safety; administrators cannot afford to misread permission levels or active sessions. I chose to enforce strict visual hierarchy and deliberate color coding so that high-risk actions (like revoking access or modifying security settings) stand out instantly, reducing the risk of accidental misconfigurations.

### What Worked
The transition from wireframing components in Figma to deploying the coded interface went remarkably smoothly. I am most satisfied with how cleanly the card components and responsive layouts translated to the live deployment. Establishing a consistent spacing rhythm and clear typography early on made building out the individual dashboard and settings views much faster and more cohesive.

### What You Would Do Differently
If I started this project over, I would invest more time upfront building a reusable CSS component library before writing page-specific styles. Doing so would have saved time when updating global padding and card states across multiple views. I also would have incorporated automated accessibility testing earlier in the development cycle to catch contrast and keyboard-navigation edge cases sooner.

### What You Learned
Building this MVP taught me a lot about the actual weight of cognitive offloading in tool design. Designing for technical domains like IAM forces you to realize that simplicity isn't just about removing elements—it is about structuring necessary complexity so the user stays in control without feeling overwhelmed. I also gained a much deeper appreciation for managing the full lifecycle from an initial design file all the way to a live, responsive production deployment.
