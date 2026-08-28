Ryn Sears, section 9/10

Regarding the duplicate folders and issues I had in lab:
There were multiple 'node_modules' folders so npm dependencies had been installed at more than one folder level. The extra folder was "csc-3100-app/packages/react-frontend/node_modules" instead of csc-3100-app/node_modules". I got rid of this extra folder so the project uses the shared root `node_modules` and root `package-lock.json`. I do not know how this happened but things to seem to be working normal with no more duplicate folders.
Additionally, MyApp.jsx was missed an import to get data from Table.jsx and a default export.
