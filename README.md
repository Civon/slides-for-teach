# Reavel.js slide gnerator
<!-- FIXME: slide.md become hyper-link auto, which is not i wanted -->
## Origin code fork from [wl00887404@github](wl00887404.github.io)

### Steps

1. yarn install
2. create a sub-floder and get into it
3. new a setting.json and slides.md (see [example](./test))
4. enjoy writing your slide in slides.md 
5. after writing, gernate index.html by command 

```bash 
yarn md <arg>
# <arg> is which sub-floder of project your slide.md in
```

### Detail 

first vertical slides stack will gernate by html in [Template](./template) floder,
if not set in setting.json in each sub-floder as below type.
```json 
template: "jenny.html"
```
then, will auto gernate by //template/default.html 
