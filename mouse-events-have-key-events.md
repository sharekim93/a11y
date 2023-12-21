# mouse-events-have-key-events

`onMouseOver` / `onMouseOut` 을 사용할 때는
`onFocus` / `onBlur` 를 같이 사용하여 접근성을 높인다.

<div onMouseOver={fn} onFocus={focusFn}>

<div onMouseOut={fn} onBlur={focusFn}
