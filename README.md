# Front End Development

This repository contains all the weekly exercises and projects for the
**Front End Development** course.\
Each branch holds both the **starter** and **finished** files for each
week.

## Getting Started

Follow these steps to set up the project locally:

### Clone the Repository

Use **git** to clone this repository to your local machine:

``` bash
git clone <repository-url>
cd <repository-folder>
```

> Replace `<repository-url>` with the actual URL of this repo.

### Install Dependencies

Install all required packages using **npm**:

``` bash
npm install
```

### Run the Project

Start the development server to preview the project in your browser:

``` bash
npm run dev
```

or, if the project uses a different script (such as `npm run dev`), run
the appropriate command.

## Branch Structure

Each **branch** represents a specific **week** of the course: 
- `week-1-starter` / `week-1-finished`
- `week-2-starter` / `week-2-finished`
- ... and so on.

Switch to the relevant branch to access the files for that particular week:
  
``` bash
git checkout week-1-starter
```

or

``` bash
git checkout week-1-finished
```

## Folder Layout (per branch)

Typical branch structure:

    /public        # Static assets
    /src           # Source code
    package.json   # Project configuration and dependencies
    README.md      # This file

## Requirements

-   **Node.js** (latest LTS recommended)
-   **npm** (comes with Node.js)

You can verify installation with:

``` bash
node -v
npm -v
```

## Notes

-   Make sure to install dependencies after switching branches, as
    different weeks might introduce new packages.
-   Check the branch's own instructions (if any) for week-specific tasks
    or scripts.

## License

This project is intended for educational purposes.\
Refer to the course or instructor for any specific licensing details.

### Author

Front End Development Team / David Schol
