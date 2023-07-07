Open Submitter
====

The goal: a template-based open source web automation engine with Chrome browser emulation support. Users may build their own templates in Javascript using puppeteer, run them in multithreading mode, publish templates in templates gallery and earn money from other customers when they spend funds on captcha services.

### Todo list:

- ✅ UI kit
- ⏳ Templates engine
- ✅ Multithreading
- ❌ Templates gallery backend at opensubmiiter.com
- ❌ Scripts for automatic builds
- ❌ Revenue sharing system
- ❌ Official website
- ❌ Templates documentation

### Cloning the project

```
git clone --recursive https://github.com/MoterHaker/opensubmitter.git
cd opensubmitter
npm install
npm run dev
```

For Windows users: git longpaths must be enabled to deal with "File name too long" errors:

```
git config --system core.longpaths true
```