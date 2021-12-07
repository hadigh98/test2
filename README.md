
​<p align="center"><img src="https://media-exp1.licdn.com/dms/image/C4D0BAQG9DjYkEPGwXQ/company-logo_200_200/0/1571819949440?e=2159024400&v=beta&t=2qw7hsgBU7rOH4O35DuMj6Efo2OukpIWFOGJRXcAZZE" width="150"></a></p>
<p align="center" >Welcome to Sher Yadet Nare`s document  </p>



## Table of content
- [Routes](#routes)
    - [Web routes](#web-routes)
    - [Api routes](#api-routes)
 
- [Controller](#controller)
	- [Auth controllers](#auth-controllers)
    - [Game controllers](#game-controllers)
	- [User controllers](#user-controllers)
    - [V2 controllers](#v2-controllers) 

- [Middlewares](#Middlewares)
- [Requests](#Requests)
	- [V2 requests](#v2-requests)

- [Jobs](#jobs)
	- [Package Jobs](#package-jobs)
	
- [Mail](#mail)

- [Models](#models)
	- [Game model](#game-model)
	- [MongoDB model](#mongoDB-model)

- [Database](#database)
	- [factories](#factories)
	- [migrations](#migrations)
	- [seeds](#seeds)


- [Views](#views)

 	- [emails](#emails)

    



## Routes

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 1500 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

### Web routes

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 1500 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

### Api routes

#### https://api.sheryadetnare.ir/api/rp/v1/test/game/question


| Name       | Value |
| :---:      |    :----:   |
| Endpoint   | "rp/v1/test/game/question" |
| Controller | Game\GameController        |
| Method     | TestGameQuestions        |
| Http verb  | GET        |
| Header     | -        |

#### Response
```
{
    "status": "success",
    "msg": "finish questions",
    "count_not_reviewed": 0
}
```


#### https://api.sheryadetnare.ir/api/rp/v1/test/game/question/active


| Name       | Value |
| :---:      |    :----:   |
| Endpoint   | "rp/v1/test/game/question/active" |
| Controller | Game\GameController        |
| Method     | TestGameQuestions        |
| Parameter  | questions_id , hardship_level |
| Http verb  | POST        |
| Header     | -        |

#### Response
```
{
    "status": "success",
    "msg": "success"
}
```


#### https://api.sheryadetnare.ir/api/rp/v1/test/game/question/inactive


| Name       | Value |
| :---:      |    :----:   |
| Endpoint   | "rp/v1/test/game/question/inactive" |
| Controller | Game\GameController        |
| Method     | TestGameQuestionsInactive  |
| Parameter  | questions_id , hardship_level |
| Http verb  | POST        |
| Header     | -        |

#### Response
```
{
    "status": "success",
    "msg": "success"
}
```
## Controller

### Auth controllers
### Game controllers
### User controllers
### V2 controllers


## Requests

### V2 requests


## Jobs

### Package jobs


## Mail

## Models

### Game model
### MongoDB

## Database

### factories

### migration

### seeds


## Views
### emails


## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the Laravel [Patreon page](https://patreon.com/taylorotwell).

### Premium Partners

-   **[Vehikl](https://vehikl.com/)**
    
-   **[Tighten Co.](https://tighten.co)**
    
-   **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
    
-   **[64 Robots](https://64robots.com)**
    
-   **[Cubet Techno Labs](https://cubettech.com)**
    
-   **[Cyber-Duck](https://cyber-duck.co.uk)**
    
-   **[Many](https://www.many.co.uk)**
    
-   **[Webdock, Fast VPS Hosting](https://www.webdock.io/en)**
    
-   **[DevSquad](https://devsquad.com)**
    
-   **[Curotec](https://www.curotec.com/services/technologies/laravel/)**
    
-   **[OP.GG](https://op.gg)**
    
-   **[CMS Max](https://www.cmsmax.com/)**
    
-   **[WebReinvent](https://webreinvent.com/?utm_source=laravel&utm_medium=github&utm_campaign=patreon-sponsors)**
    
-   **[Lendio](https://lendio.com)**
    
-   **[Romega Software](https://romegasoftware.com)**
    

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).​



