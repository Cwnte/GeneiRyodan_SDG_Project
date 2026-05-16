About the Project
Rice farmers in Nueva Ecija, Philippines face a 35–42% yield gap caused by timing-based inefficiencies in irrigation and fertilization that traditional farming calendars can no longer reliably address under today's climate volatility.
AgriBridge is an Offline-First Progressive Web App (PWA) that bridges this gap. It provides precise, data-driven prescriptions for crop management — running entirely on a standard smartphone — without requiring a stable internet connection. By processing locally entered environmental data on-device, AgriBridge helps smallholders:

Reduce fertilizer waste by up to 20% through precision scheduling
Lower irrigation-related fuel and electricity costs by up to 12%
Identify optimal harvest windows with 90% accuracy to preserve grain quality and maximize market value

This project directly advances UN Sustainable Development Goals SDG 2 (Zero Hunger), SDG 8 (Decent Work and Economic Growth), and SDG 12 (Responsible Consumption and Production) by democratizing precision agriculture for rural communities who cannot afford industrial agritech infrastructure.

Target Users: Smallholder rice farmers managing 1.5–2.5 hectares in rural Nueva Ecija; agricultural cooperative officers; field extension workers.


The Problem It Solves
Traditional rice farming in Central Luzon relied on generational ecological knowledge that has been disrupted by escalating climate volatility. The region now experiences thermal peaks of 35°C in May and precipitation surges of 390.5 mm in August, decoupling fixed farming calendars from actual crop phenology.
This creates three compounding productivity losses:
ProblemImpactMistimed fertilizer application~25% nitrogen lost to leaching and volatilizationSuboptimal irrigation scheduling15–20% yield reduction during critical reproductive phasesPremature or delayed harvesting12% post-harvest loss from grain shattering or quality degradation
Existing precision agriculture solutions require constant internet connectivity and expensive hardware — both unavailable to rural populations. AgriBridge removes these barriers by running complex decision logic directly on the device.

Key Features

📶 Offline-First Operation — Functions for at least 5 consecutive days without any internet connection using local data storage and service worker caching
🌱 Growth Stage Prediction — Tracks rice phenology using Growing Degree Day (GDD) accumulation rather than fixed calendar dates
💧 Irrigation Scheduling — Recommends dynamic irrigation timing based on crop growth phase and local thermal data entered by the user
🌿 Fertilizer Prescriptions — Provides nitrogen application schedules aligned with physiological crop requirements, minimizing runoff waste
📅 Harvest Window Identification — Predicts a 3-day optimal harvest window with 90% accuracy to maximize grain quality and marketable surplus
🌐 Bilingual Interface — Full support for English and Filipino (Tagalog) to serve farmers and field workers in their preferred language
📱 Mobile-First Design — Optimized for entry-level Android smartphones with no app store installation required (installable as a PWA)
🔄 Background Sync — Queues data locally and syncs anonymized cooperative-level data when connectivity is restored
