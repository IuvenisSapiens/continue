import ClassPropertyRef from '@site/src/components/ClassPropertyRef.tsx';

# FileTreeContextProvider

The ContextProvider class is a plugin that lets you provide new information to the LLM by typing '@'.
When you type '@', the context provider will be asked to populate a list of options.
These options will be updated on each keystroke.
When you hit enter on an option, the context provider will add that item to the autopilot's list of context (which is all stored in the ContextManager object).

[View the source](https://github.com/continuedev/continue/tree/main/continuedev/src/continuedev/libs/llm/filetree.py)

## Properties

<ClassPropertyRef name='title' details='{&quot;title&quot;: &quot;Title&quot;, &quot;default&quot;: &quot;tree&quot;, &quot;type&quot;: &quot;string&quot;}' required={false} default="tree"/><ClassPropertyRef name='display_title' details='{&quot;title&quot;: &quot;Display Title&quot;, &quot;default&quot;: &quot;File Tree&quot;, &quot;type&quot;: &quot;string&quot;}' required={false} default="File Tree"/><ClassPropertyRef name='description' details='{&quot;title&quot;: &quot;Description&quot;, &quot;default&quot;: &quot;Add a formatted file tree of this directory to the context&quot;, &quot;type&quot;: &quot;string&quot;}' required={false} default="Add a formatted file tree of this directory to the context"/><ClassPropertyRef name='dynamic' details='{&quot;title&quot;: &quot;Dynamic&quot;, &quot;default&quot;: true, &quot;type&quot;: &quot;boolean&quot;}' required={false} default="True"/><ClassPropertyRef name='requires_query' details='{&quot;title&quot;: &quot;Requires Query&quot;, &quot;description&quot;: &quot;Indicates whether the ContextProvider requires a query. For example, the SearchContextProvider requires you to type &#x27;@search &lt;STRING_TO_SEARCH&gt;&#x27;. This will change the behavior of the UI so that it can indicate the expectation for a query.&quot;, &quot;default&quot;: false, &quot;type&quot;: &quot;boolean&quot;}' required={false} default="False"/><ClassPropertyRef name='workspace_dir' details='{&quot;title&quot;: &quot;Workspace Dir&quot;, &quot;type&quot;: &quot;string&quot;}' required={false} default=""/>

### Inherited Properties
