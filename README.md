This is an experimental repo for testing out hugo theme by [hugo-brewm](https://github.com/foxihd/hugo-brewm). 
> under construction 🚧👷🏻‍♀️
1. Create new repo
2. Run:

```bash
hugo new site **mysite**
```

```bash
cd **mysite**

```
```bash
git init
```

2. Import theme
```bash
git submodule add **[github link] [themes/...]**
```

3. Add `theme = "..."` to site's configuration in `config.toml`.

```bash
echo 'theme = "..."' >> config.toml
```

4. Initialize theme on new clone
```bash
git submodule update --init --recursive
```
5. (optional) page find:
```bash
npx pagefind --site "public"
```
