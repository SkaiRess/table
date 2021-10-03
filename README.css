/* User's Styled Elements: Tabs */
.use-tabs {
  position: relative;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;

  --c-tab: 0 0%;
  --c-border: var(--color-border, #ddd);
}

.use-tabs > div:not([data-dynamic]) {
  flex: 1 0 100%;
  min-width: 100%;
}

.use-tabs > div > div {
  display: none;
  padding: 12px 0;
}

.use-tabs > .active:nth-child(1) ~ div > div:nth-child(1),
.use-tabs > .active:nth-child(2) ~ div > div:nth-child(2),
.use-tabs > .active:nth-child(3) ~ div > div:nth-child(3),
.use-tabs > .active:nth-child(4) ~ div > div:nth-child(4),
.use-tabs > .active:nth-child(5) ~ div > div:nth-child(5),
.use-tabs > .active:nth-child(6) ~ div > div:nth-child(6),
.use-tabs > .active:nth-child(7) ~ div > div:nth-child(7),
.use-tabs > .active:nth-child(8) ~ div > div:nth-child(8),
.use-tabs > .active:nth-child(9) ~ div > div:nth-child(9),
.use-tabs > .active:nth-child(10) ~ div > div:nth-child(10),
.use-tabs > .active:nth-child(11) ~ div > div:nth-child(11),
.use-tabs > .active:nth-child(12) ~ div > div:nth-child(12),
.use-tabs > .active:nth-child(13) ~ div > div:nth-child(13),
.use-tabs > .active:nth-child(14) ~ div > div:nth-child(14),
.use-tabs > .active:nth-child(15) ~ div > div:nth-child(15),
.use-tabs > .active:nth-child(16) ~ div > div:nth-child(16),
.use-tabs > .active:nth-child(17) ~ div > div:nth-child(17),
.use-tabs > .active:nth-child(18) ~ div > div:nth-child(18),
.use-tabs > .active:nth-child(19) ~ div > div:nth-child(19),
.use-tabs > .active:nth-child(20) ~ div > div:nth-child(20) {
  display: block;
}

.use-tabs > [data-dynamic] {
  display: inline-block;
  padding: 4px 16px;
  margin: 4px;
  border: 2px solid;
  border-radius: 40px;
  color: hsla(var(--c-tab) 64% / 100%); /* Light: 46%; Dark: 64% */
  line-height: 24px;
  cursor: pointer;
  user-select: none;
}

.use-tabs > [data-dynamic]:hover {
  background: hsla(var(--c-tab) 32% / 12%); /* Light: 78%; Dark: 32% */
}

.use-tabs > [data-dynamic].active {
  color: hsl(var(--c-tab) 92% / 100%); /* Light: 18%; Dark: 92% */
  background: hsla(var(--c-tab) 32% / 16%); /* Light: 78%; Dark: 32% */
}

/* Test colors */
.use-tabs > .active.--pink {
  --c-tab: 350deg 100%;
}
.use-tabs > .active.--blue {
  --c-tab: 230deg 100%;
}
.use-tabs > .active.--green {
  --c-tab: 120deg 100%;
}



/* Vertical */
@media (min-width: 960px) {
  .use-tabs.--vertical {
    display: grid;
    grid-template-columns: 212px 1fr;
    padding: 8px 0;
    border: 1px solid var(--c-border);
    border-radius: 3px;
  }
  .use-tabs.--vertical > div:not([data-dynamic]) {
    grid-column: 2;
    grid-row: 1 / 50; /* max tabs */
    margin: -8px 0;
    border-left: 1px solid var(--c-border);
  }
  .use-tabs.--vertical > div > div {
    padding: 18px 24px;
  }
  .use-tabs.--vertical > [data-dynamic] {
    display: block;
    grid-column: 1;
    padding: 8px 16px;
    margin: 0;
    border: none;
    border-radius: 0;
  }
}



/* Vertical + Right */
@media (min-width: 960px) {
  .use-tabs.--vertical.--right {
    grid-template-columns: 1fr 212px;
  }
  .use-tabs.--vertical.--right > div:not([data-dynamic]) {
    grid-column: 1;
    border-left: 0;
    border-right: 1px solid var(--c-border);
  }
  .use-tabs.--vertical.--right > [data-dynamic] {
    grid-column: 2;
  }
}



/* Ripple */
.use-tabs.--ripple > [data-dynamic] {
  position: relative;
  overflow: hidden;
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}
.use-tabs.--ripple > [data-dynamic]::after {
  content: '';
  position: absolute;
  top: 50%;
  left: 50%;
  width: 72%;
  padding-top: 72%;
  background: inherit;
  border-radius: 50%;
  opacity: 0;
  transform: translate3d(-50%, -50%, 0);
  pointer-events: none;
}
.use-tabs.--ripple > [data-dynamic]:not(.active):hover::after {
  animation: 1s switch-focus--vertical ease infinite;
}
.use-tabs.--ripple > [data-dynamic].active::after {
  animation: switch-tap--vertical 0.24s cubic-bezier(0.55, 0.06, 0.68, 0.19);
}



/* Tabline */
.use-tabs.--tabline {
  justify-content: flex-start;
}
.use-tabs.--tabline > [data-dynamic] {
  padding: 6px 10px;
  margin: 0;
  background: transparent;
  border: 2px solid transparent;
  border-radius: 0;
}
.use-tabs.--tabline > [data-dynamic].active {
  border-bottom: 2px solid hsla(var(--c-tab) 92% / 100%); /* Light: 18%; Dark: 92% */
}
.use-tabs.--tabline > div:not([data-dynamic]) {
  margin-top: -1px;
  border-top: 1px solid var(--c-border);
}
