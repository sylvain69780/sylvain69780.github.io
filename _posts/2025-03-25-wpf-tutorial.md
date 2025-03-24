# WPF application

To demonstrate a new WPF component for my work, I followed a tutorial available on YouTube.

[SingletonSean - Models - WPF MVVM TUTORIAL #1](https://www.youtube.com/watch?v=fZxZswmC_BY)

* I highly recommend this tutorial, as it thoroughly establishes a credible model before progressing to the associated views.
* The View design serves as an excellent introduction to XAML, covering grid layouts, padding, margins, shared sizes, and (keyed) styles.
* The creation of the ViewModels shows bindings, UpdateSourceTrigger.

Below the domain presented in the video.

I used Mermaid to build this diagram.

::: mermaid
classDiagram
    Hotel "1" --> "1" ReservationBook : owns
    ReservationBook "1" --> "*" Reservation : registers
    Reservation "1" --> "1" RoomID : for
::: 

![C# Diagram](../assets/images/reservoom.png)


