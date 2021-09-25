# 🎨 Colorize
When you develop discord bots, you have to use colors in your embeds. Either you have a color code beforehand, or you usually spend a lot of time choosing a color that suits you by trial and error...

In order to solve this problem, the `@discord-factory/colorize` module provides you with a wide range of colors based on the [tailwind](https://tailwindcss.com/docs/customizing-colors) color palette.

## Getting started
In order to use the module, you must first have installed it with the following command :
```bash
npm install @discord-factory/colorize
yarn add @discord-factory/colorize
```

You can now use it in your embeds as below :
```ts
import Colors from '@discord-facory/colorize'
import { MessageEmbed } from 'discord.js'

const embed = new MessageEmbed({
  description: 'My embed !',
  color: Colors.INVISIBLE, 👈 // Please select your prefered color
})
```

## License
[MIT](./LICENSE) License © 2021 [Baptiste Parmantier](https://github.com/LeadcodeDev)
