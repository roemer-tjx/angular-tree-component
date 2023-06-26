# angular tree component
This is a fork of [@circlon/angular-tree-component](https://github.com/CirclonGroup/angular-tree-component).
As it seems that they abandoned the project I decided to do some development on it and make it support Ivy and upper versions of Angular.
## Getting started

Install `angular-tree-component`:

```npm install @ali-hm/angular-tree-component```

Import `TreeModule`:

```
import { TreeModule } from '@ali-hm/angular-tree-component';

@NgModule({
  declarations: [AppComponent],
  imports: [TreeModule],
  bootstrap: [AppComponent]
})
export class AppModule {}
```

Add css to `styles.scss` or include in `angular.json`:

```
@import '~@ali-hm/angular-tree-component/css/angular-tree-component.css';
```

## Docs, Demos & More

## Support

## Angular supported version

angular-tree-component supports angular 14 and above, and AoT compilation.

## Contributing


