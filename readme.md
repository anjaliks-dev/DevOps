
# Project Title
A brief description of what this project does and who it's for

## Acknowledgements
 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)


## API Reference

#### Get all items
```http
  GET /api/items
```
| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item
```http
  GET /api/items/${id}
```
| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)
Takes two numbers and returns the sum.


## Appendix
Any additional information goes here


## Authors
- [@octokatherine](https://www.github.com/octokatherine)


## Badges
Add badges from somewhere like: [shields.io](https://shields.io/)
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

## Color Reference
| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Example Color | ![#0a192f](https://via.placeholder.com/10/0a192f?text=+) #0a192f |
| Example Color | ![#f8f8f8](https://via.placeholder.com/10/f8f8f8?text=+) #f8f8f8 |
| Example Color | ![#00b48a](https://via.placeholder.com/10/00b48a?text=+) #00b48a |
| Example Color | ![#00d1a0](https://via.placeholder.com/10/00b48a?text=+) #00d1a0 |


## Contributing
Contributions are always welcome!
See `contributing.md` for ways to get started.
Please adhere to this project's `code of conduct`.

## Demo
Insert gif or link to demo

## Deployment
To deploy this project run
```bash
  npm run deploy
```

## Environment Variables
To run this project, you will need to add the following environment variables to your .env file
`API_KEY`
`ANOTHER_API_KEY`

