# Log
## Day 1: July 1, 2020
**Today's Progress:**
1. React(120 mins)

**Thoughts:**
Worked on some React. Went through a lecture that discussed that React returns JavaScript- even though JSX looks like HTML, it is not HTML. In the example below, that is all JavaScript.
```
...
return (
  <div className="content-toggle">
    <button onClick={handleClick} className={summaryClassName}>
      Tacos
    </button>
    {isOpen && (
      <div className="content-toggle-details">
        <p>
          A taco is a traditional Mexican dish composed of a corn or
          wheat tortilla folded or rolled around a filling.
        </p>
      </div>
    )}
  </div>
);
```
Discussed declarative vs imperitive, the proper terms such as `props` (for items that look like HTML attributes, they are props in React). We also talked about side-effects and hooks.

**Today's Links:**
1. [React Training](https://github.com/ReactTraining)