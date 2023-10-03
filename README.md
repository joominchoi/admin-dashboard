# The Odin Project: Admin Dashboard Project

Building an admin dashboard

Check it out [here](https://jooomin.github.io/admin-dashboard/)

**Course reference pages:**
[Project: Admin Dashboard](https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-admin-dashboard)

## Thoughts
- The sidebar icons were disappearing when I added the final privacy icon. I managed to figure out
that their size needs to be explicitly set but I need to look into why they disappeared without this
property. Was it because they exceeded the size of the given grid? If so, why did the icons not
disappear (set to 0x0) previously when I was adding the icons one by one?
- Drawing a rough skeleton of the page on paper and approaching the task in bite size pieces makes the task a lot more approachable and less overwhelming

## Learnings
- Use position:relative to 'overlap' elements
- The box-sizing property allows us to include the padding and border in an element's total width and height.

## Recapping
- Use of minmax(x, y) where x is the minimum size and y is the maximum size
- Use of css selectors like nth child to select specific elements without having to give the element a classname or id
