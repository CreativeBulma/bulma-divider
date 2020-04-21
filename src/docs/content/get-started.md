---
title: "Get Started"
date: "2020-03-21"
menu: "main"
weight: 2
draft: false
---

# Get started
**You only need 1 CSS file to use BulmaDivider**

## Installation
### First, let's install the component!
There are several ways to get started with BulmaDivider.

{{< tabs tabTotal="3" tabID="1" tabName1="1. NPM" tabName2="2. CDN" tabName3="3. Github" >}}
{{< tab tabNum="1" >}}
Use npm to install the `bulma-divider` package **recommended**
```shell
npm install @creativebulma/bulma-divider
```
{{< /tab >}}

{{< tab tabNum="2" >}}
Use the [jsDelivr](https://jsdelivr.com) CDN to link to the BulmaDivider stylesheet
```html
https://www.jsdelivr.com/package/npm/@creativebulma/bulma-divider
```
{{< /tab >}}

{{< tab tabNum="3" >}}
Use the GitHub repository to get the latest development version.

Download from the repository [https://github.com/CreativeBulma/bulma-divider/tree/master/dist/](https://github.com/CreativeBulma/bulma-divider/tree/master/dist/)
{{< /tab >}}
{{< /tabs >}}

## Usage
All you have to do is to add a container with the `divider` class and with the text you want to display as value.

### Styles
#### Horizontal (default)
{{< preview id="default" lang="html" >}}
<div>
    <div class="divider">Exemple</div>
</div>
{{< /preview >}}

#### Vertical
The divider is available in vertical style. Simply append the modifier `is-vertical` to the divider element to apply the vertical version of the divider.
{{< preview id="outlined" lang="html" >}}
<div style="display: flex;">
    <div style="flex: 1;height: 200px; background-color: #f4f5f8"></div>
    <div class="divider is-vertical">And</div>
    <div style="flex: 1;height: 200px; background-color: #f4f5f8"></div>
</div>
{{< /preview >}}

### Colors
{{< preview id="colors" lang="html" >}}
<div>
    <div class="divider is-info">Info</div>
    <div class="divider is-success">Success</div>
    <div class="divider is-warning">Warning</div>
    <div class="divider is-danger">Danger</div>
    <div class="divider is-info is-light">Info light</div>
    <div class="divider is-success is-light">Success light</div>
    <div class="divider is-warning is-light">Warning light</div>
    <div class="divider is-danger is-light">Danger light</div>
</div>
{{< /preview >}}

### Alignement
The divider is available in different alignements (by default divider text is centered).

To change the divider alignment, use the `is-left` or `is-right` modifier on the `divider`:
{{< preview id="alignment" lang="html" >}}
<div>
    <div class="divider is-left">Left</div>
    <div class="divider">Centered</div>
    <div class="divider is-right">Right</div>
</div>

<p>When applied to a vertical divider alignments are converted to <code>top</code> and <code>bottom</code> alignements.</p>
<div style="display: flex;">
    <div style="flex: 1;height: 100px; background-color: #f4f5f8"></div>
    <div class="divider is-vertical is-left">And</div>
    <div style="flex: 1;height: 100px; background-color: #f4f5f8"></div>
</div>
<br />
<div style="display: flex;">
    <div style="flex: 1;height: 100px; background-color: #f4f5f8"></div>
    <div class="divider is-vertical">And</div>
    <div style="flex: 1;height: 100px; background-color: #f4f5f8"></div>
</div>
<br />
<div style="display: flex;">
    <div style="flex: 1;height: 100px; background-color: #f4f5f8"></div>
    <div class="divider is-vertical is-right">And</div>
    <div style="flex: 1;height: 100px; background-color: #f4f5f8"></div>
</div>
{{< /preview >}}