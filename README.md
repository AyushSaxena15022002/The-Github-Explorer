https://the-github-explorer-application.netlify.app/

GitHub Explorer is a React-based frontend Web Platform that allows users to explore GitHub users, view detailed profiles, and visualize repository statistics through interactive charts and cards. Users can log in to the platform, perform searches for GitHub users, and access comprehensive information about their repositories, followers, stars, and forks.

It is a Single Page Application which uses the feature of Router and Routes to render 3 different sections of components namely dashboard , login and error pages as per login and authorization.

In this project I have used Auth0 which provides authentication and authorization services as Auth0 has simple implementation and good documentation. It helped me to provide private and guarded route to the dasboard for users who logged in , denied access otherwise navigating them back to login .
 
State Management in react is a difficult task thereby the project makes good use of Context Api using which I was able to create global context and use features like useContext to communicate between components to avoid prop-drilling. I have used a http library named AXIOS to deal with http requests(mostly all fetch requests) and used global context to carry the results between diferent components.

Using FusionCharts library I have created interactive and visually appealing charts and graphs namely PIE3D , Column3D , Doughnut2D and Bar3D to display information about the repos like stars , languages , forks , etc.   

Styled-components library helped me to provide CSS to several components individually and used global styles otherwise.
I have used 2 column layout for the charts and represented them in 2fractions and 3fractions of the width of the web page and also ensured that heights are also adjusted accordingly to maintain the responsivenes of the site.

This project helped me to solidify my react skills to build Dynamic websites with User-friendly interfaces. 

The major challenges were :
1.) Analysing and structuring flow of functionality to render data and components.
2.) Studying and Researching about the working of Gitub Api and making specific api calls to get appropriate data which can be displayed.
3.) Defining particular components for Enabling the private routes which provide authentication and authorization using auth0.
