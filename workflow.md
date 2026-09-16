## Workflow

### Step 1: Initialize the Ifc7 project

```
ifc init
```

### Step 2: Add the interfaces owned by the project

```
ifc add ./api/schemas.json schemas
ifc add ./api/shipping-status.yaml shipping-api
```

### Step 3: Commit the changes locally

```
ifc commit
```

### Step 4: Push the changes to the ifc7.dev hub

```
ifc login
ifc push
```

### Step 5: Generate client code from the interface documents

```
ifc generate
```
