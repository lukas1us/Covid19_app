#Covid19 overview app

Available on Gitub pages: https://lukas1us.github.io/Covid19_app/

Data source from https://www.jhu.edu/ official API, link down below.

![global_chart](https://github.com/lukas1us/Covid19_app/blob/master/readme_github/covidapp_global.png)

Covid19 App is my first react project. Inspiration for this project was youtube channel 'JavaScript Mastery' and his video - https://www.youtube.com/watch?v=khJlrj3Y6Ls.

Thanks to this video I could learn basic concepts of React Framework (component structure, fetching API, using class, async/await, hoooks) and eventually build "real-world" web application.

As beginner I used out create-react-app "tool/repository" by facebook to get started quickly.

Libraries used in this project:

- @material-ui/core
- axios
- react-chartjs-2
- react-countup
- classnames

Hooks:

- useState
- useEffect

APi:
https://covid19.mathdro.id/api

This App takes data from API - number of infected, recovered and deaths caused by infectious disease COVID-19 - and save it into state.data object. Thanks to library "react-chartjs-2" I can import Line and Bar charts and represent data as "flow chart".

![czechia_chart](https://github.com/lukas1us/Covid19_app/blob/master/readme_github/covidapp_detail.png)
