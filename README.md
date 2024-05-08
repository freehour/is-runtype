# Is Type

Type checking functions for TypeScript.

### Functions

```typescript
function isType(arg: unknown, type: string): boolean;
function isFunction(arg: unknown): arg is (...args: any[]) => any;
function isArray(arg: unknown): arg is any[];
function isObject(arg: unknown): arg is object;
function isNumber(arg: unknown): arg is number;
function isString(arg: unknown): arg is string;
function isBoolean(arg: unknown): arg is boolean;
function isSymbol(arg: unknown): arg is symbol;
```

### Installation

#### npm

```bash
npm install is-runtype
```

#### bun

```bash
bun install is-runtype
```
