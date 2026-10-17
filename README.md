# Angular, Ionic & PetCare Coursework

This repository is a collection of small web-development exercises and application experiments. It includes an Ionic/Angular pet-care app named **PetPal**, several smaller practice projects, and a separate Python server folder.

Because these folders were built for different exercises, this repository is a learning workspace rather than one unified application.

## Main app: PetPal

The `PetPal/` folder contains an Ionic + Angular application. The routed UI includes pages for home, authentication, a dashboard, shop, profile, vets, vaccines, and contact/about information, along with reusable UI components.

### Tech stack

- Angular 20 and TypeScript
- Ionic Angular
- Capacitor
- RxJS

### Run PetPal

Requires a Node.js version compatible with the installed Angular/Ionic toolchain.

```bash
cd PetPal
npm install
npm start
```

To create a production build:

```bash
npm run build
```

## Other folders

The repository also contains separate practice examples such as a calculator, feedback form, student grade tool, to-do app, TypeScript exercises, and other web-development demos. Check the `package.json` inside each app folder before running it.

The root `server/` directory is a separate Python project; it is not assumed to be connected to PetPal without integration code being configured and tested.

## Development notes

- This is a coursework and practice collection; not every folder is intended to be deployed.
- Run each app from its own directory where a `package.json` is present.
- Do not commit virtual environments, Python bytecode, Node dependencies, generated build output, or local `.env` files.
- Verify frontend/API integration and app-specific setup before presenting any folder as a complete end-to-end product.

## Author

**Beauty Mauryaa** · [GitHub](https://github.com/BeautyMauryaa)
