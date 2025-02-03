## 🌟 Nature in Paradise

A hugo powered static website for Nature in Paradise

### Prerequisites

To contribute effectively, you'll need some prerequisites installed on your machine:

- **Hugo Extended v0.127+**: [[https://gohugo.io/installation/](https://gohugo.io/installation/)]
- **Node v18+**: [[https://nodejs.org/en/download/](https://nodejs.org/en/download/)]
- **Go v1.22+**: [[https://go.dev/doc/install](https://go.dev/doc/install)]

### Install Dependencies

Install all the necessary dependencies using the following command:

```bash
npm install
```

### Development Command

Start the development server using the following command:

```bash
npm run dev
```

### Preview Command

Start the production server to preview your changes and test functionality:

```bash
npm run preview
```

````


### Build Command

Build the project for production, generating optimized static files:

```bash
npm run build
````

### Format Command

Format HTML and .md file:

```bash
npm run format
```

_Upon formating HTML per above command, You may receive a series of errors having to do with these modules:_  
node_modules/prettier  
node_modules/prettier-plugin-go-template

As of 10 November 2024, these errors do not seem to impact performance.

### Contributing Your Changes

Push changes directly to:  
https://github.com/natureinparadise/natureinparadise.github.io/

### Maintainers

- [Dave Klinges](https://github.com/dklinges9)

## Navigation / Important Directories and Files

_Edit the Menu_: config/_default/menus.en.toml  
\_Edit Site Pages_: most pages are stored in content/english  
_Documents_: content/english/docs/ Having a docs/ folder in the root no longer works for hyperlinking
_Images_: assets/images/ (NOT the root images/ dir. That's a derived property)  
_Contact page_: configs/\_default/params.toml
