# Vanadium Hackathon Template

This is straight boiler-plate using:

Frontend: NextJS, Typescript, Chakra UI

Backend: FastAPI, Python

Install dependencies (you might have to run this command in both the frontend and backend)

```bash
yarn install
```

Then you can run the frontend with:

```bash
yarn workspace frontend dev
```

Then you can run the backend on a different terminal instance:

```bash
yarn workspace backend dev
```

Troubleshooting Errors:

If you are having initial erroring in front-end code, make sure you are using the workspace version of typescript. 
You can check this through command pallete ```CRLT``` + ```SHIFT``` + ```P``` then typing ```Typescript: Select Typescript Version```

If you are having issues reciving server responces from the backend please ensure you are using node version < 18.
*template was build on v16.16.0


#### Note: If you see something that can be improved, please make a PR
