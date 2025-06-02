Literature Survey
1. Why Road Maintenance Matters
We rely on roads every day—whether it's for commuting to work, transporting goods, or just getting from point A to point B. But roads don’t stay in good shape on their own. Cracks, potholes, and worn-out markings slowly creep in, making travel less safe and more frustrating. Traditionally, detecting road damage meant sending people out to manually inspect streets—a process that’s not only slow and costly but also often inaccurate. With cities growing and roads aging, we need smarter, faster ways to keep our infrastructure in check.

2. Smarter Detection with AI and Computer Vision
Thanks to recent breakthroughs in Artificial Intelligence (AI) and computer vision, spotting road damage no longer has to be a manual chore. AI models—especially advanced ones like Vision Transformers (ViT)—can now analyze road images and accurately detect issues like:

Potholes

Surface cracks (longitudinal, transverse, or fatigue-related)

Faded markings

Eroded edges

Unlike older models that focused on smaller image areas, ViTs look at the whole picture using a technique called self-attention, which makes them great at spotting even subtle damage. In real-world testing on datasets like RDD2020, these models achieved accuracy rates over 90%, proving they’re not just fast—they’re reliable too. SafeStreet builds on this with a multi-label model, meaning it can detect more than one issue in a single photo—just like a human would.

3. How Mobile Apps Put the Power in Your Hands
Imagine seeing a pothole and being able to report it in just a few taps. That’s exactly what mobile apps like SafeStreet’s aim to do. Built using React Native, the app lets anyone—citizens or city workers—report issues by:

Taking or uploading a photo

Automatically tagging their location

Optionally describing the damage

The app supports multiple languages and is designed to be intuitive even for users who aren’t tech-savvy. By making it easy to report problems on the go, the app turns every citizen into a contributor to safer roads.

4. The Tech Behind the Scenes: Backend Systems
While the app gets most of the attention, the real magic happens behind the scenes. SafeStreet’s backend uses cloud-based infrastructure and RESTful APIs to handle everything from image uploads to AI analysis. With a MongoDB database and scalable cloud services like AWS or GCP, the system can handle thousands of reports without slowing down.

Right now, AI processing is done in the cloud for higher accuracy, but there's also support for edge computing in the future—meaning the app could one day run AI directly on users’ phones, especially useful in low-connectivity areas.

5. Talking to a System That Actually Listens: Chatbots & NLP
Not everyone wants to fill out forms or navigate apps. Some just want to type or speak naturally—and get things done. That’s where chatbots powered by Natural Language Processing (NLP) come in. SafeStreet uses AI models like Gemini or GPT to enable a friendly, conversational interface where users can:

Report an issue

Check on the status of their report

Ask about different types of road damage

Get contact info for local maintenance departments

The chatbot supports multiple languages and is smart enough to handle unclear inputs or escalate to human help when needed. It makes the system more inclusive and easier to use for everyone.

6. Staying Updated: Notifications That Matter
People want to know what’s happening after they report a problem. SafeStreet keeps everyone in the loop with real-time notifications through:

Email updates

In-app alerts and push notifications

SMS (especially for users in areas with low internet access)

These alerts update users when their issue is received, when action is taken, and when the repair is complete. It builds transparency and trust—two things that are often missing in public service systems.

7. Following Through: From Report to Resolution
SafeStreet doesn’t stop at just identifying the problem—it sees it through to the end. Here’s how the full cycle works:

A user reports a problem through the app or chatbot

The image is processed by AI to detect and classify the damage

Local authorities review and validate the report

Maintenance teams are assigned and repairs are made

The issue is marked as resolved, with an updated photo

The original reporter gets a follow-up and can rate the resolution

This kind of end-to-end workflow ensures issues are not just tracked—they’re solved, and people are kept informed throughout.

8. Respecting Privacy and Building Trust
With photos and location data involved, privacy is a serious concern—and SafeStreet takes it seriously. The platform follows global data protection standards like GDPR and India’s DPDP Bill. Key measures include:

Asking for clear user consent before collecting data

Encrypting all data in storage and transit

Automatically blurring faces or license plates in images

Limiting access to sensitive data through role-based permissions

By putting privacy first, SafeStreet ensures that helpful technology doesn’t come at the cost of personal safety.

9. How SafeStreet Compares to Other Systems
Many platforms exist out there—some use Google Street View, some rely on crowd-sourced photos, others use AI. But most only cover part of the picture. Here’s how SafeStreet stands out:

Feature	SafeStreet	Others
Real-time AI detection	✅	❌ or limited
Multi-label damage classification	✅	❌
Mobile & web support	✅	Some only web
End-to-end lifecycle tracking	✅	❌
Chatbot & multilingual NLP support	✅	Rare
Cloud + edge AI support	✅	❌
Data privacy compliance	✅	Not always clear

SafeStreet is built as a complete platform, combining the best of AI, user experience, and public service design.

10. Final Thoughts: A Smarter Way to Fix Our Streets
Road maintenance doesn’t have to be slow, frustrating, or inefficient. With tools like SafeStreet, we can turn every citizen into a sensor, every report into an insight, and every issue into an opportunity for smarter city management. By combining cutting-edge AI, thoughtful design, and real-world usability, SafeStreet isn’t just another reporting app—it’s a step toward building cities that work better for everyone.

