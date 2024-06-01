## Electron based desktop application for [notion.so](https://www.notion.so) (Linux only as official apps are available for macOS and Windows)

Forked from [tokozedg/notion.so](https://github.com/tokozedg/notion.so)

**To Build**

```bash
git clone [[this repo]]
cd notion.so
npm install
npm run build
npm run deb
```

This will create an application in the `dist/notion-linux-x64` folder and deb
package in `dist/installers/`.

Install the deb package using the following command:

```bash
sudo dpkg -i dist/installers/notion.so_2.0.0_amd64.deb
```

Uninstall the app using the following command:

```bash
sudo dpkg -r notion.so
```
