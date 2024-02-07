# Movie App

This movie demo app showcases the power of modern Android development with Jetpack Compose and Navigation Compose. With a sleek and intuitive user interface, 
the app allows users to explore a curated list of movies, complete with detailed information such as movie images, director details, release date, actors, and plot.

The app features two main screens: the first screen displays a list of movies, each accompanied by a movie image and essential details. 
Users can easily browse through the list to discover new movies of interest. Upon selecting a movie item, users are seamlessly navigated to the movie details screen.

On the movie details screen, users can explore further into the selected movie, accessing comprehensive information and a horizontal scroll view of additional movie images.

# Jetpack Compose
- Jetpack compose is the new way to build UI for your android applications in a declarative manner. Now no more XML needed and you can build Android apps without construct the XML layout code.
- Jetpack Compose is a modern declarative UI Toolkit for Android. Compose makes it easier to write and maintain your app UI by providing a declarative API that allows you to render your app UI without imperatively mutating frontend views.
- Using Compose, you can build your user interface by defining a set of composable functions that take in data and emit UI elements.

# Navigation Compose

Navigation helps you in understanding how your app moves across different components in your Application. Android JetPack Navigation helps in implementing your high-level navigation in a go easy approach.

The Navigation Component is made up of three major parts:

1. **Navigation Graph**: This is a resource that collects all navigation-related data in one place. This includes all of the locations in your app, referred to as destinations, as well as the possible paths a user could take through your app. It’s like a big book that has all the places you can go in an app and how you can move between them. Think of it as a map and a guide combined.
2. **NavHost**: This is a unique composable that you can include in your layout. It shows various destinations from your Navigation Graph. The NavHost links the NavController with a navigation graph that specifies the composable destinations that you should be able to navigate between. As you navigate between composables, the content of the NavHost is automatically recomposed. Each composable destination in your navigation graph is associated with a route.
3. **NavController**: The NavController is the central API for the Navigation component. It is stateful and keeps track of the back stack of composables that make up the screens in your app and the state of each screen.

