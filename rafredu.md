# Snippet content:
```JSX
import {$NAME$State} from "@/context/ui/$NAME$Provider";

type $NAME$ActionType =
    | { type: '$ActionType1$'; }
    | { type: '$ActionType2$'; }

export const $TM_FILENAME_BASE$ = (state: $NAME$State, action: $NAME$ActionType): $NAME$State => {
    switch (action.type) {
        case '$ActionType1$':
            return {
                ...state,
            }
        case '$ActionType2$':
            return {
                ...state,
            }
        default:
            return state;
    }
}
```

## Variables
```JSX
$NAME$
Expression:
Default Value: "_NAME_"

$ActionType1$
Expression:
Default Value: "_Action1_"

$ActionType2$
Expression:
Default Value: "_Action2_"

$TM_FILENAME_BASE$ 
Expression: capitalize(camelCase(fileNameWithoutExtension()))
Default Value: ""
```
