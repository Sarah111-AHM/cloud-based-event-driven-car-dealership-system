
Paper Analysis: Rangu (2025)

1. Research Title
Enhancing Dealer Communication in Automotive through Digital Real-time Solutions

2. Publication Year
2025(Volume 5, Issue 1 of the International Journal of IoT).

3. Main Problem Addressed
This paper addresses the critical communication inefficiencies within the modern automotive retail ecosystem.It identifies that traditional, manual communication methods (phone calls, emails, static websites) between manufacturers, dealerships, and customers are too slow, fragmented, and error-prone. This leads to poor customer experience, missed sales opportunities, operational friction, and an inability to meet contemporary demands for instant, accurate, and personalized information regarding inventory, pricing, promotions, and services.

4. Proposed Solution
The author proposes a holistic digital transformation framework centered on theconvergence of Artificial Intelligence (AI) and Cloud technologies to create real-time digital communication solutions. The core components of this framework are:

· AI-Powered Communication Tools: Deployment of chatbots, virtual assistants, and predictive analytics to provide instant, 24/7 customer service, personalize interactions, and proactively anticipate customer needs (e.g., service reminders, vehicle recommendations).
· Cloud-Based Integration Platforms: Utilization of centralized cloud platforms (e.g., Salesforce Automotive Cloud, Microsoft Azure, AWS) to enable seamless, real-time data sharing across the automotive value chain. This ensures all stakeholders have synchronized access to live information on inventory, pricing, customer profiles, and manufacturer updates.
· Data-Driven Decision Making: Leveraging the integrated data flow for strategic insights, optimized inventory management, and targeted marketing.
· Extension to Emerging Trends: The framework also considers integration with IoT for smart dealerships and autonomous vehicle (AV) data, preparing for future communication needs like vehicle health monitoring and V2X (Vehicle-to-Everything) interactions.

5. Limitations or Gaps

· High-Level and Conceptual Focus: The paper provides a broad, strategic overview of trends and benefits but lacks granular technical details on system architecture, specific implementation protocols, or data schema design necessary for actual development.
· Assumption of Resource Availability: The proposed adoption of advanced AI and cloud platforms may not adequately address the significant financial, technical, and change management barriers for small to mid-sized dealerships, a challenge it mentions but does not deeply resolve.
· Peripheral Treatment of Core DMS Functions: While communication is a vital module, the paper does not delve into the architectural design or integration of other essential Dealer Management System (DMS) pillars, such as comprehensive inventory management, detailed service department operations, complex financial transaction processing, and in-depth reporting analytics.
· Underdeveloped Security Architecture: Although data security and regulatory compliance (GDPR, CCPA) are highlighted as "crucial," the discussion remains at the policy level. There is a gap in proposing concrete, implementable security architectures (e.g., authentication models, data encryption in transit/at rest, microservices security) within the proposed real-time system.

6. How Our Proposed Project Differs/Improves
Our proposedAutosales DMS project differs and builds upon this work in the following key ways:

· From Conceptual Framework to Concrete Architecture: While Rangu (2025) outlines the "why" and "what" of digital communication, our project focuses on the "how." We aim to design and specify a concrete, implementable system architecture. For instance, where this paper advocates for real-time data, we would engineer it using specific technologies like event-driven patterns (Apache Kafka) and microservices.
· Comprehensive System vs. Communication Channel: This paper is primarily focused on enhancing the communication channel. Our DMS is a complete business management platform. We would integrate the proposed AI/Cloud communication layer as one component within a larger system encompassing inventory, sales, service, finance, and human resources, ensuring data flows seamlessly between all modules.
· Architectural Depth and Technical Specificity: Our project will address the technical gaps by defining specific APIs, database models, service decomposition (microservices design), and deployment strategies. We will prioritize designing a scalable and secure backend architecture that can support the real-time features described in the paper, moving beyond conceptual benefits to address implementation challenges.
· Balanced Innovation and Practicality: We will consider the resource constraints of various dealership sizes by proposing a modular architecture. This would allow for scalable adoption, where core DMS functions can be implemented first, with advanced AI communication modules added as needed.

7. Classification
Closely Related

Justification: This paper is directly and highly relevant to the core objective of our Autosales DMS project. It authoritatively establishes the critical industry problem (inefficient dealer communication) and validates the central technological thesis of our project: that a modern DMS must be built on AI, cloud, and real-time data principles to be effective. It serves as an excellent justification for our project's direction and provides a feature set (AI chatbots, cloud integration, predictive analytics) that our system architecture must be designed to support and technically enable.

---

Comparative Summary and Project Positioning

Aspect Rangu (2025) - Current Paper Khriji et al. (2021) - Previous Paper (REDA) Our Proposed Autosales DMS Project
Primary Domain Automotive Business & Communication IoT & Sensor Data Processing Automotive Business Management (DMS)
Core Problem Fragmented, slow business communication in automotive retail. Processing high-volume, real-time telemetry from sensor networks. Inefficient, non-integrated, and non-real-time management of all dealership operations.
Proposed Solution AI + Cloud for real-time digital communication channels. Event-driven microservices architecture (Kafka, MQTT) for data streams. A unified platform integrating both domains: Using an event-driven, microservices architecture (inspired by Khriji) to power AI-driven, real-time business communication and operations (inspired by Rangu).
Relation to Our Work Defines the "What" & "Why" - The essential features and business rationale. Provides the "How" - A relevant technical architectural pattern for real-time data flow. Synthesis & Implementation - Combines the business logic/features from Rangu with a robust technical architecture inspired by Khriji, adapted for complex business transactions.
Classification Closely Related (Business Problem & Features) Partially Related (Technical Architecture Pattern) The Target System

The analysis of these two papers together powerfully frames your graduation project. Rangu (2025) provides the business context, justification, and feature requirements for a next-generation DMS. Khriji et al. (2021) offers a proven technical blueprint for handling real-time data flows, which can be adapted from sensor telemetry to business events (e.g., "Vehicle Sold," "Service Requested," "Inventory Updated")
