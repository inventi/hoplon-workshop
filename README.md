# holpon-workshop

## Dependencies

- java 1.7+
- [boot][1]
- Clojrue IDE - use your favorite. For those who never tired Clojure and coming from Java - you can use [Cursive] [2]. Just install it into Intellij IDEA as a plugin and register for free Cursive licence.


## Usage
### Development
1. Start the `dev` task. In a terminal run:
    ```bash
    $ boot dev
    ```
    This will give you a  Hoplon development setup with:
    - auto compilation on file changes
    - audible warning for compilation success or failures
    - auto reload the html page on changes
    - Clojurescript REPL

2. Go to [http://localhost:8000][3] in your browser. You should see "Hello, Hoplon!".

3. If you edit and save a file, the task will recompile the code and reload the
   browser to show the updated version.

## License

Copyright © 2017, **Inventi**

[1]: http://boot-clj.com
[2]: https://cursive-ide.com
[3]: http://localhost:8000
[4]: http://hoplon.io
