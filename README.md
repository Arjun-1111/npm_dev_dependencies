# npm_dev_dependencies

# for nodeJS(TypeScript)

# npm install express zod config cors express mongoose pino pino-pretty dayjs bcrypt jsonwebtoken lodash nanoid

# npm install @types/body-parser @types/config @types/cors @types/express @types/node @types/pino @types/bcrypt @types/jsonwebtoken @types/lodash @types/nanoid ts-node-dev typescript -D

#eslint and prettier config

# npm install eslint eslint-config-airbnb eslint-config-prettier eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-node eslint-plugin-prettier eslint-plugin-react prettier @typescript-eslint/eslint-plugin @typescript-eslint/parser -D


eslint file
# .eslintrc.json
{
  "extends": ["airbnb", "prettier", "plugin:@typescript-eslint/recommended"],
  "plugins": ["prettier"],
  "rules": {
    "prettier/prettier": "error",
    "spaced-comment": "off",
    "no-console": "warn",
    "consistent-return": "off",
    "func-names": "off",
    "object-shorthand": "off",
    "no-process-exit": "off",
    "no-param-reassign": "off",
    "no-return-await": "off",
    "no-underscore-dangle": "off",
    "class-methods-use-this": "off",
    "prefer-destructuring": ["error", { "object": true, "array": false }],
    "no-unused-vars": ["error", { "argsIgnorePattern": "req|res|next|val" }]
  }
}

.prettierrc
{
  "singleQuote": true
}


# most common dependencies
"dependencies": {
    "bcryptjs": "^2.4.3",
    "dotenv": "^7.0.0",
    "express": "^4.16.4",
    "express-mongo-sanitize": "^1.3.2",
    "express-rate-limit": "^3.5.0",
    "helmet": "^3.16.0",
    "hpp": "^0.2.2",
    "jsonwebtoken": "^8.5.1",
    "mongoose": "^5.5.2",
    "morgan": "^1.9.1",
    "nodemailer": "^6.1.1",
    "slugify": "^1.3.4",
    "validator": "^10.11.0",
    "xss-clean": "^0.1.1"
  },
