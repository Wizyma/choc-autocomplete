Changelog

- New multiple prop
- New AutoCompleteTag component
- Input can Now be controlled
- Now built on hooks
- Automatic list scroll
- `_fixed` pseudo prop to style fixed items
- Allow custom filter method
- onChangeProps new provides values array, when it's multiple
- onSelectOption params changed - `click` to `mouse`
- New onOptionFocus method
- New `AutoCompleteGroupTitle` component. `AutoCompleteGroup` no longer takes a title prop.
- `AutoCompleteFixedItem` is not exported, just add `fixed` prop to `AutoCompleteItem`

Todo

- onTagRemoved Function for multi Tags

```ts
export interface AutoComplete extends Omit<BoxProps, "onChange"> {
  //   children?: MaybeRenderProp<AutoCompleteChildProps>;
  creatable?: boolean | ((props: CreatableProps) => ReactNode);
  emphasize?: boolean | CSSObject;
  // onChange?: (value: string) => void;
  // emptyState?: boolean | ReactNode;
  //   rollNavigation?: boolean;
  // focusInputOnSelect?: boolean;
  // freeSolo?: boolean;
  // selectOnFocus?: boolean;
  // openOnFocus?: boolean;
  // defaultIsOpen?: boolean;
  // onSelectOption?: (params: OptionEvent) => boolean | void; //TODO come beack for newInput
  // onOptionFocus?: (params: OptionEvent) => boolean | void;
  // suggestWhenEmpty?: boolean;
  // closeOnSelect?: boolean;
  // closeOnBlur?: boolean;
  // shouldRenderSuggestions?: (value: string) => boolean;
  // maxSuggestions?: number;
  // multiple: boolean;
  // onTagRemoved: (removedTag: Item["value"], tags: Item["value"][]) => void;
}
```
