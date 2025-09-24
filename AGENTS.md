## Important Rules

- Use functional TypeScript, no classes
- Use `type` over `interface`, never use `any`
- Use function declarations instead const+arrow function
- Functions signatures should accept a single object argument rather than multiple, positional arguments
- Minimize or avoid usage of React useEffect and useState
- Group React state in objects with `{status:"state_name",...rest}` so I can do discriminated unions
- Use `node:` prefixed imports
- Do not add extensions in module imports eg. `import b from './b.js'` is wrong, use `from './b'`!
- Never remove commented-out code
- Never use Emojis
- Keep implementation lean and simple, avoid unnecessary abstractions
- Be critical and push back when you think something is a bad idea
- Security is paramount
