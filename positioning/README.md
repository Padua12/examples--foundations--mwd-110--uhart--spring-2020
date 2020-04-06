# Positioning

## Offset Properties

`top`, `right`, `bottom`, and `left`.

Example

```css
h1 {
   top: 10px;
   left: 30px;
}

header {
   bottom: -30px;
   right: -400px;
}

```

---

## Static
* Default/initial value to positioned items
* Doesn’t break flow
* Doesn’t observe offset properties
* Stacking context (`z-index`) isn’t observed
* Does scroll with the document

---


## Relative
* Doesn’t break flow
* Observes offset properties
* Stacking context (`z-index`) is observed
* In the absence of offset properties, it simply behaves as though it’s `static`
* Does scroll with the document

---

## Fixed
* Does break flow
* Observes offset properties
* Stacking context (`z-index`) is observed
* In the absence of offset properties, a fixed positioned item will be rendered in it’s original location
* Does not scroll with the document
* Binds to the viewport; makes the viewport its parent
* Offset properties are offset from the viewport

---

## Absolute

---

## Sticky
