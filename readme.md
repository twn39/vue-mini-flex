### Install

    yarn add vue-mini-flex

or 

    npm i vue-mini-flex --save

### Useage

*import*

```js
  import 'vue-mini-flex/flex/flex.css'
  import FlexRow from 'vue-mini-flex/flex/flex-row.vue'
  import Flex from 'vue-mini-flex/flex/flex.vue'
  import FlexColumn from "vue-mini-flex/flex/flex-column.vue";
```

*sample 1:*
```html
      <flex-row justifyContent="center" alignItems="center">
        <flex flex="1" justifyContent="center">
            <span>
                flex 1/3
            </span>
        </flex>
        <flex flex="2">
          flex 2/3
        </flex>
      </flex-row>
```

*sample 2:*

```html
      <flex-row>
        <flex flex="1">
          flex 1/10
        </flex>
        <flex flex="2">
          flex 2/10
        </flex>
        <flex flex="3">
          flex 3/10
        </flex>
        <flex flex="4">
          <flex-column>
            <flex>flex</flex>
            <flex>flex</flex>
          </flex-column>
        </flex>
      </flex-row>
```

