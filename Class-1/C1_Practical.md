# Class 1 : Practical Assignment
## Hello World program using just HTML.
    <body>
        <div id="root">
            <h1>Hello World</h1>
        </div>
    </body>

## Hello World program using just js.
    <body>
        <div id="root"></div>
    
        <script>
            let heading = document.createElement(h1);
            heading.innerHTML = "Hello World";
            let root = document.getelementById("root");
            root.appendChild(h1);
        </script>
    </body>

## Hello World program using just React.js.⚛️
    <body>
        <div id="root"></div>
    

        <script
            crossorigin
            src="https://unpkg.com/react@18/umd/react.development.js"
        ></script>
        <script
            crossorigin
            src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"
        ></script>

        <script>
            let heading = React.CreateElement('h1',{
                //props id: 'heading'
            }, 'hello React');

            let root = ReactDOM.createRoot(document.getelementById('root'));

            root.render(heading);
        </script>
    </body> 
