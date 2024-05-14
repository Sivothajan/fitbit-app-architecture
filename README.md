# fitbit-app-architecture

&nbsp;
## Folder Structure

A new application typically begins with the following folder structure:

<pre class="language-markdown"><code class="language-markdown">/app/
/common/
/companion/
/resources/
/settings/
</code></pre>

<blockquote>The <code>/common/</code>, <code>/companion/</code>, and <code>/settings/</code> folders are optional.</blockquote>

&nbsp;
## Size

The maximum size of an application at installation time is <code>10</code> megabytes. The total file system space used by an installed is limited to <code>15</code> megabytes, including any resources, and files written using the [File System API](https://dev.fitbit.com/build/reference/device-api/fs/).

&nbsp;
## JavaScript

The <code>/app/</code>, <code>/common/</code> and <code>/companion/</code> folders can contain multiple JavaScript (.js) or TypeScript (.ts) files.

During the build process, the scripts are automatically compiled, bundled and optimized by the [TypeScript](https://www.typescriptlang.org/) compiler and [rollup.js](https://rollupjs.org/). This produces a single [ECMAScript 5.1](https://262.ecma-international.org/5.1/) file for the application, and another file for the companion.

JavaScript is run on the device using the [JerryScript engine](http://jerryscript.net/).

The <code>/settings/</code> folder should contain a single [React JSX](https://facebook.github.io/react/docs/introducing-jsx.html) file, named <code>index.jsx</code>.
