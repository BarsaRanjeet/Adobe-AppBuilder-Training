Below is the description of the Adobe appbuilder training session:

Hello everyone, my name is Ranjeet Barsa. I'm excited to start a new series on Adobe App Builder, a game-changing tool that's transforming how we work with Adobe Commerce and other Adobe solutions.

With App Builder, we are no longer limited to traditional Adobe Commerce modules. Adobe has given us the power to extend e-commerce applications and seamlessly integrate with other platforms like never before.

We are moving away from the old model of tightly coupled monolithic Magento/Adobe Commerce applications where everything was part of one system. Instead, we are embracing a microservices approach where features and integrations are broken into separate apps connected through APIs.

These apps can now be maintained independently, offering a level of flexibility and scalability that we've never seen before.

Adobe Commerce is already a powerful Enterprise-grade platform with robust core features, modular customization, and a marketplace of extensions. It's designed for large enterprises that often manage multiple channels, touchpoints, and third-party integrations.

As these businesses grow, the need to break components apart becomes essential. Rather than adding everything directly into the core system, App Builder allows developers to build external applications that work alongside the core platform using a microservices architecture.

This separation not only improves performance but also makes scaling, maintenance, and automation much easier.

Although the focus of this series is App Builder, I wanted to mention that Adobe has already rolled out several innovative services like Live Search, Catalog Service, Product Recommendations, and API Mesh.

These tools enhance existing features and bring fresh solutions to optimize Adobe Commerce projects, offloading tasks and helping create Enterprise-grade applications that are among the best in the market.

Before we dive into what App Builder is, let's take a moment to reflect on the history of Magento, now known as Adobe Commerce, and the direction we are heading.

The journey started with the launch of Magento 1. As you know, Magento began as a monolithic application.

All parts of the system—front end, back end, database interactions, and business logic—were tightly integrated into a single codebase. This meant the entire application had to be scaled as a whole, which limited flexibility.

Then came Magento 2, which, while still monolithic, brought significant improvements. It introduced Magento Cloud, which offloaded the burden of hosting and maintenance to cloud services.

A major turning point came when Adobe acquired Magento. This marked the shift toward a headless architecture where the front end and back end were decoupled.

We saw improvements in REST APIs and the introduction of GraphQL APIs. With headless architecture, we were no longer tied to old PHTML files, enabling modern frontend technologies like PWAs and frameworks like Vue Storefront.

Today, we are in a phase where we are decoupling even further. Adobe has begun rolling out new composable services like Live Search, Product Recommendations, Price Indexer, and Payment Services that are now external and scale independently.

Adobe has gone even further with Adobe App Builder, a framework created to help us adopt and build composable architecture ourselves.

So, what exactly is Adobe App Builder? It is a powerful platform that allows us to build, manage, and run custom apps on Adobe's cloud infrastructure.

We can create custom services that integrate seamlessly with Adobe Commerce. This is a major leap forward for flexibility and scalability.

App Builder includes the Adobe Developer Console to manage projects and APIs, and developer tools like the `aio` CLI and Spectrum React components to simplify the process.

It also features Adobe I/O Runtime, a serverless infrastructure for hosting apps, and Adobe I/O Events for real-time asynchronous integrations.

Webhooks are available for synchronous calls triggered by Adobe Commerce events, ideal for immediate responses like calculating order totals or verifying payments.

We can embed single-page applications (SPAs) directly into the Adobe Commerce admin panel, eliminating the need for XML-based configurations.

API Mesh allows for combining multiple data sources into a single GraphQL endpoint, which simplifies integration and accelerates development.

What can we create? Custom integrations for external systems like PIM or ERP. Adobe has prepared an Integration Starter Kit to help with this.

We can build real-time event handling for order notifications, inventory updates, or shipping fee calculations using synchronous webhooks.

We can also create SPAs using React Spectrum components to build custom frontend applications within the admin panel.

With these possibilities comes responsibility. As developers, we need to adjust our mindset and move from monolithic thinking to a microservices architecture.

We are no longer dealing with a single codebase where everything lives under one roof. Each service—payments, inventory, or customer data—can exist on its own and communicate via APIs.

The benefits are huge: faster deployment cycles, greater flexibility to swap parts of the system, and improved scalability by only scaling the parts that need it.

Existing projects can continue running their current platform as-is while using these new tools to modernize at their own pace.

This gradual approach helps eliminate technical debt and enhances backend integrations without a complete system rebuild.

We will cover all the topics day vise

let's go with setup