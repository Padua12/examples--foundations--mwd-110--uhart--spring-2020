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

---


## Relative
* Doesn’t break flow
* Observes offset properties
* Stacking context (`z-index`) is observed
* In the absence of offset properties, it simply behaves as though it’s `static`

---

## Fixed

---

## Absolute

---

## Sticky
