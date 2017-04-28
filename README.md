# theam. Stack Templates
_Project templates for `stack new` that we use_

## How to use these templates

### 1. Copy the **raw** link for the template

i.e. `https://github.com/theam/stack-templates/raw/master/transient-webapp.hsfiles`

### 2. Use it!

`stack new <your-project-name> https://github.com/theam/stack-templates/raw/master/transient-webapp.hsfiles`

## Specific stuff of each template

- [Transient webapp](#transient-webapp)

---

## Transient webapp

The template generates **two** `stack.yaml` files:

- `stack.yaml` - For building the _native_ code
- `client-stack.yaml` - For building with GHCJS

Also, it generates a `Build.hs` file for making the build of the
project easier.

- `stack Build.hs -h` - Prints a help message
- `stack Build.hs -a` - Builds the server *and* the GUI
- `stack Build.hs -r` - Runs the project
