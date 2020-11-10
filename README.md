

## A Frankstein Folder structure with tips took from [here](https://itnext.io/how-to-structure-a-vue-js-project-29e4ddc1aeeb) and [here](https://vueschool.io/articles/vuejs-tutorials/structuring-vue-components/).

**For more details, go there**

## Naming conventions

Here are a few conventions coming from the Vue.js official styleguide that you need to structure well your project:

- Component names should always be multi-word, except for root “App” components. Use “UserCard” or “ProfileCard” instead of “Card” for example.
Each component should be in its own file.

- Filenames of single-file components should either be always PascalCase or always kebab-case. Use “UserCard.vue” or “user-card.vue”.

- Components that are only used once per page should begin with the prefix “The”, to denote that there can be only one. For example for a navbar or a footer you should use “TheNavbar.vue” or “TheFooter.vue”.

- Child components should include their parent name as a prefix. For example if you would like a “Photo” component used in the “UserCard” you will name it “UserCardPhoto”. It’s for better readability since files in a folder are usually order alphabetically.

- Always use full name instead of abbreviation in the name of your components. For example don’t use “UDSettings”, use instead “UserDashboardSettings”.

**For more styleguides for Vue, come [here](https://learn-vuejs.github.io/vue-patterns/useful-links/)**


*Fork and feel free to start*
