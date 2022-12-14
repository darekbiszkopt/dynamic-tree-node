# ResponsiveTreeNode

This library was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.0.0.

example of tree node with custom template,
with method (expand) you can update tree node children dynamical from your services
next update soon
`<lib-node-recursion-template [treeNode]="treeNode" (expand)="nodeExpand($event)">
    <ng-template nodeTemplate let-treeNode>
      <h2>{{treeNode.label}}</h2>
    </ng-template>
</lib-node-recursion-template>`

interface using in library
`export interface TreeNodeUI {
label: string,
leaf: boolean,
loaded: boolean,
expanded: boolean,
level?: number,
children?: TreeNodeUI[]
}`

## Code scaffolding

Run `ng generate component component-name --project responsive-tree-node` to generate a new component. You can also
use `ng generate directive|pipe|service|class|guard|interface|enum|module --project responsive-tree-node`.
> Note: Don't forget to add `--project responsive-tree-node` or else it will be added to the default project in
> your `angular.json` file.

## Build

Run `ng build responsive-tree-node` to build the project. The build artifacts will be stored in the `dist/` directory.

## Publishing

After building your library with `ng build responsive-tree-node`, go to the dist folder `cd dist/responsive-tree-node`
and run `npm publish`.

## Running unit tests

Run `ng test responsive-tree-node` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Further help

To get more help on the Angular CLI use `ng help` or go check out
the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
