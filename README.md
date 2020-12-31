# Kitchen Sink Angular Material Base Module

Kitchen sink module containing all the Angular Material
components.

## Install

```
npm i @fireflysemantics/material-base-module
```

## Usage

Import and include the module in the module where you need the Angular Material components.

```
import { MaterialBaseModule } from '@fireflysemantics/material-base-module';

@NgModule({
  declarations: [
    AppComponent
  ],
  imports: [
      ...
    MaterialModule
  ],
  providers: [],
  bootstrap: [AppComponent]
})
export class AppModule { }

```

## Versioning

We will use semantic versioning so that the versions of this module match Angular Material.

## Documentation

[Module Creation Process](https://fireflysemantics.medium.com/creating-a-angular-material-kitchen-sink-base-module-6a00245b5ca9)

