### Hi! i'm TsukiGva, i'm a programmer who likes to experiment with many programming languages, i also create some of them so i can learn more about the languages i use, and learn more about how they work.


[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=TsukiGva2&theme=gruvbox)](https://github.com/anuraghazra/github-readme-stats)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=TsukiGva2&layout=compact&theme=gruvbox&hide=xc)

- Currently working on:

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=TsukiGva2&repo=Blade-lang)](https://github.com/TsukiGva2/Blade-lang)

- Languages i'm learning/want to learn:

- [X] C++
- [X] Clojure
- [ ] Ruby
- [ ] Elixir
- [ ] Rust
- [X] Python
- [X] Js

### A beautiful snippet that i want to put here:

```clojure
(defn tufparse
  [expr]
  (let [spexpr (clojure.string/split expr #" ")
        funcs (loop [[curr & remn] spexpr
               result []]
          (if (and (empty? remn) (nil? curr))
            (if (empty? result) PARSE-ERR result)
            (recur
             remn
             (conj result
                   (get functions curr curr)))))]
    (map (fn [func]
      ...
```
**From:**

[![Readme Card](https://github-readme-stats.vercel.app/api/pin/?username=TsukiGva2&repo=tuf-clojure)](https://github.com/TsukiGva2/tuf-clojure)
