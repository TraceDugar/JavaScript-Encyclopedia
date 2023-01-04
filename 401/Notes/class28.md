# Class 28 Reading Notes

(https://reactjs.org/docs/hooks-effect.html)

1. What purpose does useEffect serve in a function component compared to its counterpart(s) in class components?
In React class components, the render method itself shouldn’t cause side effects. It would be too early — we typically want to perform our effects after React has updated the DOM.

This is why in React classes, we put side effects into componentDidMount and componentDidUpdate. Coming back to our example, here is a React counter class component that updates the document title right after React makes changes to the DOM:
<br>

2. When using the useEffect Hook:
    1. What does useEffect do?
       The Effect Hook lets you perform side effects in function components.
    <br>

    2. Why is useEffect called inside a component?
       Data fetching, setting up a subscription, and manually changing the DOM in React components are all examples of side effects. Whether or not you’re used to calling these operations “side effects” (or just “effects”), you’ve likely performed them in your components before
    <br>

3. Explain the importance of properly implementing effects with Cleanup

Earlier, we looked at how to express side effects that don’t require any cleanup. However, some effects do. For example, we might want to set up a subscription to some external data source. In that case, it is important to clean up so that we don’t introduce a memory leak.
