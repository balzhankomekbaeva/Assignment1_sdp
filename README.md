Design Patterns Implemented
Singleton Pattern:
Ensures that only one instance of the CinemaConfig class exists. This class manages the global settings of the cinema (e.g., cinema name, number of screens, operating hours).

Factory Method Pattern:
Handles the creation of different types of movies, such as RegularMovie and IMAXMovie. Each movie type has its own factory class that produces instances of that movie.

Abstract Factory Pattern: 
Used to generate UI elements for different themes (e.g., DarkTheme, LightTheme). The system can dynamically generate themed UI components like buttons based on the selected theme.

Builder Pattern:
Manages the construction of complex ticket bookings, allowing for step-by-step configuration of movie titles, seat numbers, snack combos, and more.

Prototype Pattern:
Used for cloning and modifying movie schedules. The StandardSchedule class can be cloned to create new schedules with different screening times and movie details.
