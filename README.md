# Share Energy 2023 Challenge

This project was created to fulfill the Share Energy challenge, as part of its selection process.

The idea was to create a website, fullstack, where the user could, in general, log in and use APIs, both from third parties and a created one.

For more detailed information on the process, 
[visit access your repository](https://github.com/SHARENERGY-OFICIAL/desafio-sharenergy-2023-01)

## Table of contents

* [Technologies](#technologies)
* [Installation](#Installation)
* [Usage](#usage)

## Technologies

Project is created with:
* Front-end

1. ![Image](https://img.shields.io/badge/Next.js-13.1.1-yellowgreen)
2. ![Image](https://img.shields.io/badge/Typescript-4.9.4-blue)
3. ![Image](https://img.shields.io/badge/React-18.2.0-orange)
4. ![Image](https://img.shields.io/badge/TailwindCSS-3.2.4-green)
5. ![Image](https://img.shields.io/badge/Axios-1.2.2-lightgrey)
6. ![Image](https://img.shields.io/badge/Sweetalert-2.1.2-brightgreen)
---
* Back-end
1. ![Image](https://img.shields.io/badge/Prisma-4.8.0-yellowgreen)
2. ![Image](https://img.shields.io/badge/Typescript-4.9.4-blue)
3. ![Image](https://img.shields.io/badge/Fastify-4.10.2-orange)
4. ![Image](https://img.shields.io/badge/Zod-^3.20.2-green)
5. SQLite


## Installation

This project is divided into 2 parts, the front end and the back end.

### Back end
At share-energy-challenge-server paste:
```bash
npm i
npx prisma migrate dev
npm run dev
```
---
### Front end

At share-energy-challenge-web paste:
```bash
npm i
npm run dev
```
However, know that this project is deployed by vercel [in this link](https://share-energy-challenge-leandro-patricio.vercel.app/). 

That is, it is not necessary to install and open the web folder on your computer. But, IMPORTANT, to use all the functionalities of the site, the server must be running locally. When the server is needed, the site will notify you.


## Usage

To login, you will have to choose between log with the server on or off.
 * If "server on" is selected, the service will be sent to the back end, which will verify the data and return errors/validations and status.
 * If 'server off' is selected, the check will be done by the front end. 

As requested, it is possible to save user and password data in localStorage

![Image](https://freeimage.host/i/HuNUfXs)

---
Uma vez logado, você poderá navegar entre uma das 4 páginas: RandomUser, HTTP Cat, RandomDog e Lista de clients. 

1. Random User

![Image](https://ibb.co/P9NG0t4)

On this page, you will be able to see information of random people from the API [ Random User Generator](https://randomuser.me/). On hover, you can see more information about that person. You can still search and browse pages.

2. HTTP Cat

![Image](https://ibb.co/VT3QghB)

In this section you can choose an http code. If it exists in the API [ HTTP Cat](https://http.cat/), an image of a kitten will be shown. Otherwise an "umbrella" image will be shown

3. Random Dog

![Image](https://ibb.co/dtVgvmk)

Here, when clicking on the button, a doguiho from [Rancdom Dog](https://random.dog/) will appear.

4. Client List

![Image](https://ibb.co/KsY9vyD)

This is the only page that you will only be able to access through your localhost (both front and back end).
Here you can view some clients, with some other information. You will be able to edit them, delete or add a new one.

