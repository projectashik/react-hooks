## useMediaQuery

```
import { useMediaQuery } from "@cb-react/hooks"

const isMobile = useMediaQuery("(max-width: 640px)")
const isDesktop = useMediaQuery("(min-width: 1048px)")
const isTab = useMediaQuery("(min-width: 640px) and (max-width: 1048px)")
```