# Snippet content:
```JSX
import React, {FC, useReducer} from "react";
import {$NAME$Reducer} from "@/context/$NAME$/$NAME$Reducer";

export interface $NAME$State {
    $PROP$: boolean;
}

interface ProviderProps {
    children: React.ReactNode
}

const $NAME$_INITIAL_STATE: $NAME$State = {
    $PROP$: false
}

export const $TM_FILENAME_BASE$: FC<ProviderProps> = ({children}) => {

    const [state, dispatch] = useReducer($NAME$Reducer, $NAME$_INITIAL_STATE);

    return (
        <$NAME$Context.Provider
            value={{
                $PROP$: false
            }}
        >
            {children}
        </$NAME$Context.Provider>
    )
}
```

## Variables
```JSX
$NAME$
Expression:
Default Value: "_NAME_"

$PROP$
Expression:
Default Value: "_PROP1_"

$TM_FILENAME_BASE$ 
Expression: capitalize(camelCase(fileNameWithoutExtension()))
Default Value: ""
```
