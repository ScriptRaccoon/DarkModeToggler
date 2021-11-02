# Dark Mode Toggler

A simple CSS-only solution for switching between dark and light mode on a page.

Demo: https://cssdarkmodetoggler.netlify.app

The drawback of this solution is that the checkbox and the main container have to share the same parent. (This will change as soon as the `:has` selector is supported by browsers.) Of course, the JavaScript solution (see the branch [js-solution](https://github.com/ScriptRaccoon/DarkModeToggler/tree/js-solution)) does not have this restriction.
