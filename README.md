*Next Set of Laws... ASP.NET MVC (Coming Soon)*

## 🤖 Advanced Vue.js *Requires* Communication, Experience and Wide & Deep Thinking 💪

### 7️⃣ Niles' **7 Laws** for Vue.js

1. **SSG-first!** Need More? Expand to SPA, **then** SSR. Don't be dictated by trends. Understand business needs and sensibly conclude an architecture.

2. Even if your use case does not warrant a build step....consider it! Utilizing **SFC** (Single-File Components) is imperative to abiding by `SOLID` principles and coding in Vue's philosophy.

3. _Composition API > Options API_. No Discussion needed. After **countless Vue 2 ➡️ Vue 3 migrations**, converting to the Composition API has been the single best benefit to developer productivity, code organization, and utilizing best software architecture principles.

4. Utilize Pinia **early** for state management. Don't resort to hand-rolling state management composables, data will become scattered and multiple sources of truth will emerge.

5. Utilize `null` and `undefined` values on Attribute Bindings to dynamically remove HTML attributes from elements. It's one of those swiss-army knife tricks that helps in advanced templating. (Careful of the empty string `''`.)

6. Dynamic Arguments are a killer feature for abstract template creation polymorphic components - particularly in complex SPA applications with high interactivity & complexity, such as 3D, blueprints, maps and more. (I'm thinking custom event listeners, defined by outside state rather than defined on the template.)
```js
<button type=submit @[neededEvent]="triggerPolymorphicEventHandler">Create Model</button>
```

7. Utilize generic definitions over type annoations when utilizing TypeScript with `ref()`  

**Preferred**
```js
const name = ref<string | array>('niles')
```
**Only use when your type is needed in other TypeScript logic**
```js
const name: Ref<string | array> = ref('niles')
```

   
## 🤖 Advanced Laravel *Isn't* For The Weak 💪

### 🔟 Niles' **10 Rules** for Laravel:

1. **Events-Driven Architecture** is awesome...until it isn't.

2. Embrace **Modules**, **Engines**, and other monolithic organization units

3. **Interfaces** are your friend. They provide clarity, extensibility, and make documentation easier.

4. Use the Service Container to your advantage. Think about how your classes, engines, and service classes will be used via the service container at the beginning.

5. Model Events are dangerous. I know it's controversial...but I've seen it fail too many times. If you do it, it should always be class based. It makes testing against it easier - architecture testing via Pest.

6. Utilize Model Permission Guards Extensively. Lock down database access based on roles and permissions.

7. TDD is King. I know it sucks, but you will be better off.

8. Be extremely wary of Livewire, it is tempting to transfer business logic to Livewire view classes.

9. Be extremely wary of Inertia.js. It makes life easy at the beginning. Some of its limitations cause problems later on.

10. Embrace the Manager Pattern, it's powerful...if you use it for good.

<!--
**qarthandgi/qarthandgi** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
