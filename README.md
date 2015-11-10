# React BEM Decorator

> Originally based on [react-css-modules](https://github.com/gajus/react-css-modules)

## The plan:

    @bem
    class MyComponent extends React.Component {
        render() {
            return (
                <div>
                    <button elementName="button" modifiers="big fun">My Button</button>
                </div>
            );
        }
    }

Results in…

    <div class="MyComponent">
        <button class="MyComponent__button MyComponent__button--big MyComponent__button--fun">My Button</button>
    </div>