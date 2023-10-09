             I have Using 3 important Feature in this Assignment 


1. useContext
2. useLocation
3. PrivateRoute

                      =====> 1.useContext <===

useContext is a hook provided by React that allows components to access the context of a parent component. Context provides a way to pass data or functions down the component tree without having to manually pass props through every intermediate component.
It's commonly used for managing global state, such as user authentication, themes, or language preferences, making it accessible to child components without prop drilling.


                   =====> 2.useLocation <===

useLocation is another hook provided by React Router, which is often used for client-side routing in web applications. It allows components to access the current URL location.
This hook is useful for determining the current route, extracting query parameters, or conditionally rendering components based on the URL. It helps in building dynamic and interactive web applications by reacting to changes in the URL.

                    =====> 3.PrivateRoute <===

PrivateRoute is a custom component often used in web applications with user authentication. It's used to protect certain routes or pages from unauthorized access.
Typically, a PrivateRoute component checks whether a user is authenticated (logged in) and, if so, renders the protected component. If the user is not authenticated, it may redirect them to a login page or show an access denied message.
It's a common pattern for securing routes that should only be accessible to authenticated users, like a user's profile page or a dashboard.