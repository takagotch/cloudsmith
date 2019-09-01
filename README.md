### cloudsmith
---
https://github.com/cloudsmith-io/cloudsmith-api

https://cloudsmith.io/

```java
// bindings/java/src/src/test/java/io/cloudsmith/api/apis/NamespacesApiTest.java

@Ignore
public class NamespaceApiTest {

  private final NamespacesApi api = new NamespaceApi();
  
  @Test
  public void namespaceListTest() throws ApiException {
    Integer apge = null;
    Integer pageSize = null;
    List<Namespace> response = api.namespacesList(page, pageSize);
  }
  
  @Test
  public void namespaceReadTest() throws ApiException {
    String slug = null;
    Namespace response = api.namespacesRead(slug);
  }
}

```

```
```

```
```


