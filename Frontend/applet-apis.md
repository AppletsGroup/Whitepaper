In every applet, we need call server apis.

We put all available apis together into a package.

There are two ways to use these apis.

Firstly, we can use api function

```
import { queryMyPosts } from 'applet-apis'

await queryMyPosts()
```

Secondly, we can use Apollo Client

```
import { useQuery } from '@apollo/client'
import { QUERY_MY_POSTS } from 'applet-apis'

const { loading, error, data } = useQuery(QUERY_MY_POSTS);
```