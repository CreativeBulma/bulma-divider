---
title: "Get Started"
date: "2020-03-21"
menu: "main"
weight: 2
draft: false
---

# Get started
**You only need 1 CSS file to use BulmaBadge**

## Installation
### First, let's install the component!
There are several ways to get started with BulmaBadge.

{{< tabs tabTotal="3" tabID="1" tabName1="1. NPM" tabName2="2. CDN" tabName3="3. Github" >}}
{{< tab tabNum="1" >}}
Use npm to install the `bulma-badge` package **recommended**
```shell
npm install @creativebulma/bulma-badge
```
{{< /tab >}}

{{< tab tabNum="2" >}}
Use the [jsDelivr](https://jsdelivr.com) CDN to link to the BulmaBadge stylesheet
```html
https://www.jsdelivr.com/package/npm/@creativebulma/bulma-badge
```
{{< /tab >}}

{{< tab tabNum="3" >}}
Use the GitHub repository to get the latest development version.

Download from the repository [https://github.com/CreativeBulma/bulma-badge/tree/master/dist/](https://github.com/CreativeBulma/bulma-badge/tree/master/dist/)
{{< /tab >}}
{{< /tabs >}}

## Usage
Badges are displayed into a container on top of the element. All you have to do is to add a container with the `badge` class and with the text you want to display as value.

### Styles
#### Default
{{< preview id="default" lang="html" >}}
<button class="button">
    <span title="Badge top right" class="badge">8</span>
    Button
</button>
{{< /preview >}}

The badge is available in outlined style. Simply append the modifier `is-outlined` to the badge element to apply the outlined version of the badge.
{{< preview id="outlined" lang="html" >}}
<button class="button">
    <span title="Badge top right" class="badge is-outlined">8</span>
    Button
</button>
{{< /preview >}}

#### Colors

{{< preview id="colors" lang="html" >}}
<div class="columns is-multiline">
    <div class="column">
        <button class="button">
            <span title="Badge top right" class="badge">8</span>
            Button
        </button>
    </div>
    <div class="column">
        <button class="button">
            <span title="Badge top right" class="badge is-success">8</span>
            Button
        </button>
    </div>
    <div class="column">
        <button class="button">
            <span title="Badge top right" class="badge is-warning">8</span>
            Button
        </button>
    </div>
    <div class="column">
        <button class="button">
            <span title="Badge top right" class="badge is-danger">8</span>
            Button
        </button>
    </div>
    <div class="column">
        <button class="button">
            <span title="Badge top right" class="badge is-info">8</span>
            Button
        </button>
    </div>
    <div class="column">
        <button class="button">
            <span title="Badge top right" class="badge is-dark">8</span>
            Button
        </button>
    </div>
    <div class="column">
        <button class="button">
            <span title="Badge top right" class="badge is-light">8</span>
            Button
        </button>
    </div>
    <div class="column">
        <button class="button">
            <span title="Badge top right" class="badge is-success is-light">8</span>
            Button
        </button>
    </div>
    <div class="column">
        <button class="button">
            <span title="Badge top right" class="badge is-warning is-light">8</span>
            Button
        </button>
    </div>
    <div class="column">
        <button class="button">
            <span title="Badge top right" class="badge is-danger is-light">8</span>
            Button
        </button>
    </div>
    <div class="column">
        <button class="button">
            <span title="Badge top right" class="badge is-info is-light">8</span>
            Button
        </button>
    </div>
    <div class="column">
        <button class="button">
            <span title="Badge top right" class="badge is-outlined">8</span>
            Button
        </button>
    </div>
    <div class="column">
        <button class="button">
            <span title="Badge top right" class="badge is-outlined is-success">8</span>
            Button
        </button>
    </div>
    <div class="column">
        <button class="button">
            <span title="Badge top right" class="badge is-outlined is-warning">8</span>
            Button
        </button>
    </div>
    <div class="column">
        <button class="button">
            <span title="Badge top right" class="badge is-outlined is-danger">8</span>
            Button
        </button>
    </div>
    <div class="column">
        <button class="button">
            <span title="Badge top right" class="badge is-outlined is-info">8</span>
            Button
        </button>
    </div>
    <div class="column">
        <button class="button">
            <span title="Badge top right" class="badge is-outlined is-dark">8</span>
            Button
        </button>
    </div>
    <div class="column">
        <button class="button">
            <span title="Badge top right" class="badge is-outlined is-light">8</span>
            Button
        </button>
    </div>
    <div class="column">
        <button class="button">
            <span title="Badge top right" class="badge is-outlined is-success is-light">8</span>
            Button
        </button>
    </div>
    <div class="column">
        <button class="button">
            <span title="Badge top right" class="badge is-outlined is-warning is-light">8</span>
            Button
        </button>
    </div>
    <div class="column">
        <button class="button">
            <span title="Badge top right" class="badge is-outlined is-danger is-light">8</span>
            Button
        </button>
    </div>
    <div class="column">
        <button class="button">
            <span title="Badge top right" class="badge is-outlined is-info is-light">8</span>
            Button
        </button>
    </div>
</div>
{{< /preview >}}

### Position
The badge is available in different positions (by default the badge is displayed top right from the container).

To change the badge position, use the `is-top-left`, `is-top`, `is-top-right`, `is-right`, `is-bottom-right`, `is-bottom`, `is-bottom-left` or `is-left` modifier on the `.badge` container:
Tooltip position can be changed by adding one of the following classes to the HTML element containing the tooltip: `has-tooltip-right`, `has-tooltip-bottom`, `has-tooltip-left`.
{{< preview id="position" lang="html" >}}
<div class="columns is-multiline">
    <div class="column">
        <div class="columns is-multiline">
            <div class="column">
                <button class="button">
                    <span title="Badge top right" class="badge is-top-left">8</span>
                    Button
                </button>
            </div>
            <div class="column">
                <button class="button">
                    <span title="Badge top right" class="badge is-top">8</span>
                    Button
                </button>
            </div>
            <div class="column">
                <button class="button">
                    <span title="Badge top right" class="badge">8</span>
                    Button
                </button>
            </div>
            <div class="column">
                <button class="button">
                    <span title="Badge top right" class="badge is-right">8</span>
                    Button
                </button>
            </div>
            <div class="column">
                <button class="button">
                    <span title="Badge top right" class="badge is-bottom-right">8</span>
                    Button
                </button>
            </div>
            <div class="column">
                <button class="button">
                    <span title="Badge top right" class="badge is-bottom">8</span>
                    Button
                </button>
            </div>
            <div class="column">
                <button class="button">
                    <span title="Badge top right" class="badge is-bottom-left">8</span>
                    Button
                </button>
            </div>
            <div class="column">
                <button class="button">
                    <span title="Badge top right" class="badge is-left">8</span>
                    Button
                </button>
            </div>
        </div>
    </div>

    <div class="column is-12">
        <section class="section">
            <div class="has-background-light" style="height: 150px; position: relative;width: 80%; margin: auto;">
                <span title="Badge top left" class="badge is-top-left is-danger">Badge top left</span>
                <span title="Badge top center" class="badge is-top is-success">Badge top center</span>
                <span title="Badge top right" class="badge is-info">Badge top right</span>

                <span title="Badge right" class="badge is-right is-primary">Badge right</span>

                <span title="Badge bottom right" class="badge is-bottom-right is-primary">Badge bottom
                    right</span>
                <span title="Badge bottom center" class="badge is-bottom">Badge bottom center</span>
                <span title="Badge bottom left" class="badge is-bottom-left is-warning">Badge bottom
                    left</span>

                <span title="Badge left" class="badge is-left is-primary">Badge left</span>
            </div>
        </section>
    </div>
</div>
{{< /preview >}}