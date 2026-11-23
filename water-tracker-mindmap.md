# Water Tracker App: Product Mindmap

Draft for discovery and scoping. Renders in GitHub, Notion, and VS Code (Mermaid support).

```mermaid
mindmap
  root((Water Tracker App))
    Users and Jobs
      Health-conscious adults
      Fitness athletes
      Pregnant and postpartum users
      Older adults and medication users
      Parents tracking kids intake
    Core Logging
      Quick-add presets 250 ml and 500 ml
      Custom amount entry
      Edit and undo past entries
      Unit toggle ml and oz
      Log from home screen widget
      Log from lock screen and smartwatch
      Voice logging via assistant
    Goals and Targets
      Daily goal calculator
        Body weight and age
        Activity level
        Climate and weather adjustment
      Manual goal override
      Weekday or schedule-based goals
      Medical guidance disclaimer
    Reminders and Nudges
      Smart reminders within wake window
      Quiet hours and focus mode
      Adaptive frequency based on behavior
      Snooze and skip
      Notification fatigue cap
    Progress and Insights
      Daily progress ring and streak
      Weekly and monthly trends
      Intake by time of day
      Correlations with workouts and weather
    Engagement and Gamification
      Badges and milestones
      Streak freeze
      Friend challenges
      Opt-in leaderboards
    Integrations
      Apple Health and Google Health Connect
      Smartwatch sync
      Smart bottle sync
      Weather API
      Calendar-aware reminders
    Personalization
      Themes and bottle avatars
      Drink types with hydration factor
      Caffeine and alcohol adjustments
    Onboarding
      Profile setup
      Permission priming for notifications and health data
      Day-one goal reveal
    Monetization
      Free core tier
      Premium insights and integrations
      Family plan
    Data, Privacy and Trust
      Local-first storage
      Explicit health data consent
      Data export and account deletion
      GDPR and HealthKit compliance
    Platform and Tech
      iOS and Android
      Watch apps
      Offline-first with sync
      Accessibility (WCAG)
      Localization of units and languages
    Success Metrics
      North Star - Daily goal hit rate
      Input - Day-one first log rate
      Input - Reminder engagement rate
      Output - D30 retention
      Guardrail - Notification opt-out rate
```

## Suggested MVP cut (for discussion)

| Scope | Branches |
|---|---|
| MVP | Core Logging, Goals and Targets (manual + basic calculator), Reminders (basic), Progress (daily and weekly), Onboarding, Data and Privacy baseline |
| Phase 2 | Integrations (Health apps, weather), Engagement and Gamification, Personalization |
| Phase 3 | Insights correlations, Monetization tiers, Smart bottle sync, Family plan |

## Open questions to validate

1. Is the goal calculator a medical-adjacent feature? Confirm review and disclaimer requirements with Legal before launch.
2. Health data (Apple Health, Health Connect) triggers platform review and consent requirements. Confirm data-handling scope with Privacy and Security.
3. Which persona is the primary bet for MVP?
4. Does reminder adaptivity need ML, or are rules enough for v1?
