# Ember Components Diagnostic

Record your responses inside the fenced code blocks below each question.

1.  Give an example of a visual hierarchy that could be modeled with components.

    ```md
    A tree can be a visual representation of components, this can show how
    components can be nested within other components, and how they relate to
    outer routes, etc.
    ```

1.  What is the command to generate a new component called '`my-map`'?

    ```sh
    ember g component my-map
    ```

1.  What files are edited to produce a component, and what are their
    responsibilities?

    ```md
    A component.js, template.hbs, and component tests are created when a
    component is generated. The template file is the representation of the
    component on the web page. The component file is where you can place actions
    or tagnames that relate to the template file. Lastly, the component tests
    are made by ember for testing.
    ```

1.  Suppose you have a component '`my-contact`', which is loaded from
    '`app/contacts/template.hbs`' when visiting the `/contacts` path. What is
    the syntax for loading this component inside that template?

    ```html
    {{my-contact}}
    ```

    Each contact has multiple phone numbers. Suppose you also have '`my-phone`'
    nested under '`my-contact`'. What is the code you would write in
    '`app/components/my-contact/template.hbs`' to load the nested component and
    pass it data?

    ```html
    {{my-phone passedData='passedData'}}
    ```
