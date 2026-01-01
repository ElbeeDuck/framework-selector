<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SQL Complete Reference Guide</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            background: linear-gradient(to bottom right, #1e3a8a, #7c2d12, #1e3a8a);
            min-height: 100vh;
        }
        pre {
            background: rgba(0,0,0,0.3);
            border-radius: 8px;
            padding: 12px;
            overflow-x: auto;
        }
        code {
            color: #86efac;
            font-family: 'Courier New', monospace;
        }
    </style>
</head>
<body class="text-white">
    <div id="app"></div>

    <script>
        const sqlTopics = {
            start: {
                title: "SQL Complete Reference",
                subtitle: "Choose your learning path",
                options: [
                    { text: "🚀 Quick Start Guide", next: "quickstart" },
                    { text: "📊 Data Query Language (DQL)", next: "dql_menu" },
                    { text: "✏️ Data Manipulation (DML)", next: "dml_menu" },
                    { text: "🏗️ Data Definition (DDL)", next: "ddl_menu" },
                    { text: "🔗 Joins & Relationships", next: "joins_menu" },
                    { text: "🎯 Practice Examples", next: "examples" }
                ]
            },

            quickstart: {
                title: "Quick Start Guide",
                subtitle: "Essential SQL commands for immediate use",
                content: `
<div class="space-y-4">
    <div class="bg-blue-500/20 border border-blue-500/30 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">1. See Data</h3>
        <pre><code>-- Show all columns
SELECT * FROM table_name;

-- Show specific columns
SELECT column1, column2 FROM table_name;</code></pre>
    </div>

    <div class="bg-green-500/20 border border-green-500/30 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">2. Filter Rows</h3>
        <pre><code>-- Simple filter
SELECT * FROM employees WHERE department='Sales';

-- Multiple conditions
SELECT * FROM employees 
WHERE department='Sales' AND salary > 50000;</code></pre>
    </div>

    <div class="bg-purple-500/20 border border-purple-500/30 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">3. Sort Data</h3>
        <pre><code>-- Highest first
SELECT * FROM employees ORDER BY salary DESC;

-- Alphabetical
SELECT * FROM employees ORDER BY name ASC;</code></pre>
    </div>

    <div class="bg-yellow-500/20 border border-yellow-500/30 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">4. Simple Aggregates</h3>
        <pre><code>SELECT COUNT(*) FROM employees;    -- number of rows
SELECT AVG(salary) FROM employees; -- average salary
SELECT SUM(salary) FROM employees; -- total salary</code></pre>
    </div>

    <div class="bg-red-500/20 border border-red-500/30 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">5. Insert, Update, Delete</h3>
        <pre><code>-- Add a row
INSERT INTO employees (name, department, salary)
VALUES ('John Doe', 'Sales', 55000);

-- Change data
UPDATE employees
SET salary = 60000
WHERE name = 'John Doe';

-- Remove a row
DELETE FROM employees
WHERE name = 'John Doe';</code></pre>
    </div>

    <div class="bg-teal-500/20 border border-teal-500/30 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">6. Simple Join</h3>
        <pre><code>SELECT e.name, d.department_name
FROM employees e
JOIN departments d ON e.department_id = d.id;</code></pre>
    </div>

    <div class="bg-orange-500/20 border border-orange-500/30 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">✅ Basic QA Workflow</h3>
        <p class="mb-2">SELECT → WHERE → ORDER BY → INSERT / UPDATE / DELETE</p>
        <p class="text-sm text-gray-300">This is enough to check tables, filter data, and make small updates safely.</p>
    </div>

    <div class="bg-white/10 rounded-lg p-4 mt-4">
        <h3 class="text-lg font-bold mb-2">💡 Key Tips</h3>
        <ul class="space-y-1 text-sm">
            <li>• SQL is NOT case-sensitive</li>
            <li>• Every statement must end with a semicolon (;)</li>
            <li>• Use -- for comments</li>
            <li>• Shortcut in MySQL: CTRL+SHIFT+ENTER to run query</li>
        </ul>
    </div>
</div>
                `
            },

            dql_menu: {
                title: "Data Query Language (DQL)",
                subtitle: "Retrieve and analyze data",
                options: [
                    { text: "SELECT & Basics", next: "select_basics" },
                    { text: "WHERE & Filtering", next: "where_clause" },
                    { text: "Logical Operators", next: "logical_ops" },
                    { text: "Pattern Matching", next: "pattern_match" },
                    { text: "Aggregate Functions", next: "aggregates" },
                    { text: "Sorting & Limiting", next: "sort_limit" }
                ]
            },

            select_basics: {
                title: "SELECT Statement Basics",
                subtitle: "Foundation of all queries",
                content: `
<div class="space-y-4">
    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">Basic SELECT</h3>
        <pre><code>-- Select specific columns
SELECT column1, column2 FROM table_name;

-- Select all columns
SELECT * FROM customers;</code></pre>
    </div>

    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">DISTINCT - Remove Duplicates</h3>
        <pre><code>-- Get unique ages
SELECT DISTINCT age FROM Customers;

-- Get unique state values
SELECT DISTINCT state FROM customers;</code></pre>
    </div>

    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">Using Expressions</h3>
        <pre><code>-- Calculations in SELECT
SELECT (points * 10 + 20) AS discount_factor 
FROM customers;

-- Multiple calculated columns
SELECT 
    last_name,
    first_name,
    points,
    (points + 10) * 100 AS "discount factor"
FROM customers;</code></pre>
        <p class="text-sm text-gray-300 mt-2">💡 Use quotes around aliases with spaces</p>
    </div>

    <div class="bg-blue-500/20 border border-blue-500/30 rounded-lg p-4">
        <h3 class="text-lg font-bold mb-2">Operator Precedence</h3>
        <ol class="text-sm space-y-1 ml-4">
            <li>1. Parentheses ()</li>
            <li>2. Exponents (^ or **)</li>
            <li>3. Multiply/Divide/Modulus (*, /, %)</li>
            <li>4. Add/Subtract (+, -)</li>
            <li>5. Comparisons (>, <, ==, !=, <>)</li>
            <li>6. Logical Operators (AND, OR, NOT)</li>
            <li>7. Assignment (=)</li>
        </ol>
    </div>
</div>
                `
            },

            where_clause: {
                title: "WHERE Clause & Filtering",
                subtitle: "Filter records based on conditions",
                content: `
<div class="space-y-4">
    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">Basic WHERE</h3>
        <pre><code>-- Simple condition
SELECT * FROM customers
WHERE state = 'California';

-- Multiple conditions with AND
SELECT * FROM customers
WHERE country IN ('Germany', 'UK');</code></pre>
    </div>

    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">Comparison Operators</h3>
        <div class="grid md:grid-cols-2 gap-2 text-sm">
            <div><code>></code> Greater than</div>
            <div><code>>=</code> Greater or equal</div>
            <div><code><</code> Less than</div>
            <div><code><=</code> Less or equal</div>
            <div><code>=</code> Equal to</div>
            <div><code><></code> or <code>!=</code> Not equal</div>
        </div>
    </div>

    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">IN Operator</h3>
        <pre><code>-- Match any value in list
SELECT * FROM customers 
WHERE state IN ('VA', 'NY', 'CA');

-- Exclude values in list
SELECT * FROM customers 
WHERE state NOT IN ('VA', 'NY', 'CA');</code></pre>
    </div>

    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">BETWEEN Operator</h3>
        <pre><code>-- Range filtering
SELECT * FROM customers 
WHERE points BETWEEN 100 AND 200;

-- Works with dates too
SELECT * FROM orders
WHERE order_date BETWEEN '2024-01-01' AND '2024-12-31';</code></pre>
    </div>

    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">NULL Handling</h3>
        <pre><code>-- Find NULL values
SELECT * FROM customers 
WHERE phone IS NULL;

-- Find non-NULL values
SELECT * FROM customers 
WHERE phone IS NOT NULL;</code></pre>
        <p class="text-sm text-yellow-300 mt-2">⚠️ Use IS NULL, not = NULL</p>
    </div>
</div>
                `
            },

            logical_ops: {
                title: "Logical Operators",
                subtitle: "Combine multiple conditions",
                content: `
<div class="space-y-4">
    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">AND - Both conditions must be true</h3>
        <pre><code>SELECT * FROM customers
WHERE birthdate > '1990-01-01' AND points > 1000;</code></pre>
    </div>

    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">OR - At least one condition must be true</h3>
        <pre><code>SELECT * FROM customers
WHERE birthdate > '1990-01-01' OR points > 1000;</code></pre>
    </div>

    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">NOT - Negate a condition</h3>
        <pre><code>-- Using NOT
SELECT * FROM customers
WHERE NOT (birthdate > '1990-01-01' OR points > 1000);

-- Equivalent to:
SELECT * FROM customers
WHERE birthdate <= '1990-01-01' AND points <= 1000;</code></pre>
    </div>

    <div class="bg-yellow-500/20 border border-yellow-500/30 rounded-lg p-4">
        <h3 class="text-lg font-bold mb-2">⚠️ Operator Precedence</h3>
        <p class="mb-2">AND is evaluated before OR!</p>
        <pre><code>-- Without parentheses (AND evaluated first)
SELECT * FROM customers
WHERE birth_date > '1990-01-01'
OR points > 1000 AND state = 'VA';

-- With parentheses for clarity (recommended)
SELECT * FROM customers
WHERE birth_date > '1990-01-01' 
OR (points > 1000 AND state = 'VA');</code></pre>
    </div>
</div>
                `
            },

            pattern_match: {
                title: "Pattern Matching",
                subtitle: "LIKE and REGEXP operators",
                content: `
<div class="space-y-4">
    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">LIKE Operator</h3>
        <p class="text-sm text-gray-300 mb-2">Wildcards: % (any chars) and _ (one char)</p>
        <pre><code>-- Starts with 'b'
SELECT * FROM customers 
WHERE first_name LIKE 'b%';

-- Contains 'b' anywhere
SELECT * FROM customers
WHERE last_name LIKE '%b%';

-- Exactly 6 characters ending in 'y'
SELECT * FROM customers
WHERE last_name LIKE '_____y';

-- Starts with 'b', ends with 'y', 6 chars total
SELECT * FROM customers
WHERE last_name LIKE 'b____y';

-- Multiple patterns
SELECT * FROM customers
WHERE address LIKE '%trail%' OR address LIKE '%avenue%';</code></pre>
    </div>

    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">REGEXP Operator (More Powerful)</h3>
        <pre><code>-- Starts with 'a'
SELECT * FROM customers 
WHERE first_name REGEXP '^a';

-- Ends with 'ey' or 'on'
SELECT * FROM customers
WHERE first_name REGEXP 'ey$|on$';

-- Starts with 'my' or contains 'se'
SELECT * FROM customers
WHERE first_name REGEXP '^my|se';

-- Contains 'b' followed by 'r' or 'u'
SELECT * FROM customers
WHERE first_name REGEXP 'b[ru]';

-- Multiple names
SELECT * FROM customers
WHERE last_name REGEXP 'mac|field|rose';</code></pre>
    </div>

    <div class="bg-blue-500/20 border border-blue-500/30 rounded-lg p-4">
        <h3 class="text-lg font-bold mb-2">REGEXP Special Characters</h3>
        <div class="grid md:grid-cols-2 gap-2 text-sm">
            <div><code>^</code> Beginning of string</div>
            <div><code>$</code> End of string</div>
            <div><code>|</code> Logical OR</div>
            <div><code>[abc]</code> Match any single character</div>
            <div><code>[a-d]</code> Range of characters</div>
            <div><code>.</code> Any single character</div>
        </div>
    </div>
</div>
                `
            },

            aggregates: {
                title: "Aggregate Functions",
                subtitle: "Summary statistics and grouping",
                content: `
<div class="space-y-4">
    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">Common Aggregate Functions</h3>
        <pre><code>-- Count rows
SELECT COUNT(*) FROM orders;

-- Sum of values
SELECT SUM(amount) AS total_sales FROM orders;

-- Average
SELECT AVG(age) AS average_age FROM customers;

-- Maximum value
SELECT MAX(salary) FROM employees;

-- Minimum value
SELECT MIN(salary) FROM employees;</code></pre>
    </div>

    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">GROUP BY Clause</h3>
        <pre><code>-- Count by category
SELECT column_name, COUNT(*)
FROM table_name
GROUP BY column_name;

-- Average salary by department
SELECT department, AVG(salary) AS avg_salary
FROM employees
GROUP BY department;</code></pre>
    </div>

    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">HAVING Clause</h3>
        <p class="text-sm text-gray-300 mb-2">Filter groups (use after GROUP BY)</p>
        <pre><code>SELECT 
    c.customer_id,
    c.first_name,
    c.last_name,
    COUNT(o.order_id) AS total_orders
FROM customers c
LEFT JOIN orders o ON c.customer_id = o.customer_id
GROUP BY c.customer_id, c.first_name, c.last_name
HAVING COUNT(o.order_id) > 0;</code></pre>
    </div>

    <div class="bg-yellow-500/20 border border-yellow-500/30 rounded-lg p-4">
        <h3 class="text-lg font-bold mb-2">💡 WHERE vs HAVING</h3>
        <ul class="text-sm space-y-1">
            <li>• <strong>WHERE</strong>: Filters rows BEFORE grouping</li>
            <li>• <strong>HAVING</strong>: Filters groups AFTER grouping</li>
            <li>• Use WHERE for row-level conditions</li>
            <li>• Use HAVING for aggregate conditions</li>
        </ul>
    </div>
</div>
                `
            },

            sort_limit: {
                title: "Sorting & Limiting Results",
                subtitle: "ORDER BY and LIMIT clauses",
                content: `
<div class="space-y-4">
    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">ORDER BY Clause</h3>
        <pre><code>-- Sort ascending (default)
SELECT * FROM customers 
ORDER BY first_name;

-- Sort descending
SELECT * FROM customers 
ORDER BY points DESC;

-- Multiple columns
SELECT * FROM customers 
ORDER BY state, first_name DESC;

-- Sort by calculated column
SELECT *, quantity * unit_price AS total_price
FROM order_items
WHERE order_id = 2
ORDER BY total_price DESC;</code></pre>
    </div>

    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">LIMIT Clause</h3>
        <p class="text-sm text-yellow-300 mb-2">⚠️ Always comes at the end of query</p>
        <pre><code>-- Return only 3 customers
SELECT * FROM customers 
LIMIT 3;

-- Skip 6, return 3 (pagination)
SELECT * FROM customers 
LIMIT 6, 3;

-- Alternatively (clearer syntax)
SELECT * FROM customers 
LIMIT 3 OFFSET 6;</code></pre>
    </div>

    <div class="bg-blue-500/20 border border-blue-500/30 rounded-lg p-4">
        <h3 class="text-lg font-bold mb-2">📋 Complete Query Order</h3>
        <pre><code>SELECT columns
FROM table
WHERE conditions
GROUP BY columns
HAVING group_conditions
ORDER BY columns
LIMIT number;</code></pre>
        <p class="text-sm text-gray-300 mt-2">This is the correct order SQL processes clauses</p>
    </div>
</div>
                `
            },

            dml_menu: {
                title: "Data Manipulation (DML)",
                subtitle: "CRUD Operations - Create, Read, Update, Delete",
                options: [
                    { text: "INSERT - Add Data", next: "insert" },
                    { text: "UPDATE - Modify Data", next: "update" },
                    { text: "DELETE - Remove Data", next: "delete" },
                    { text: "CRUD Summary", next: "crud_summary" }
                ]
            },

            insert: {
                title: "INSERT Statement",
                subtitle: "Adding new data to tables",
                content: `
<div class="space-y-4">
    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">Insert Single Record</h3>
        <pre><code>-- Basic insert
INSERT INTO employees (name, role, salary)
VALUES ('Alice', 'Engineer', 75000);

-- Insert with NULL and DEFAULT
INSERT INTO customers(first_name, phone, points)
VALUES ('Mosh', NULL, DEFAULT);

-- Insert all columns
INSERT INTO customers (
    customer_id, first_name, last_name, birth_date,
    phone, address, city, state, points
)
VALUES (
    21, 'Barry', 'Smith', '1970-01-01',
    '555-555-5555', '2 Old Place', 'London', 'VA', 1000
);</code></pre>
    </div>

    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">Insert Multiple Records</h3>
        <pre><code>-- Bulk insert
INSERT INTO customers(first_name, phone, points)
VALUES 
    ('Mosh', NULL, DEFAULT),
    ('Bob', '1234', 10),
    ('Alice', '5678', 150);</code></pre>
    </div>

    <div class="bg-green-500/20 border border-green-500/30 rounded-lg p-4">
        <h3 class="text-lg font-bold mb-2">✅ Best Practices</h3>
        <ul class="text-sm space-y-1">
            <li>• Always specify column names (don't rely on order)</li>
            <li>• Use DEFAULT for auto-increment or default values</li>
            <li>• Use NULL explicitly for missing optional values</li>
            <li>• Bulk inserts are faster than multiple single inserts</li>
        </ul>
    </div>
</div>
                `
            },

            update: {
                title: "UPDATE Statement",
                subtitle: "Modifying existing data",
                content: `
<div class="space-y-4">
    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">Basic UPDATE</h3>
        <pre><code>-- Update single column
UPDATE employees
SET salary = 80000
WHERE name = 'Alice';

-- Update multiple columns
UPDATE customers
SET city = 'London', state = 'UK'
WHERE customer_id = 1;</code></pre>
    </div>

    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">Update with Calculations</h3>
        <pre><code>-- Increase all salaries by 10%
UPDATE employees
SET salary = salary * 1.10;

-- Conditional update
UPDATE employees
SET salary = salary * 1.15
WHERE department = 'Sales';</code></pre>
    </div>

    <div class="bg-red-500/20 border border-red-500/30 rounded-lg p-4">
        <h3 class="text-lg font-bold mb-2">⚠️ Critical Warning</h3>
        <p class="text-sm mb-2">Forgetting WHERE updates ALL rows!</p>
        <pre><code>-- DANGEROUS - Updates every row!
UPDATE employees
SET salary = 50000;

-- SAFE - Only updates specific rows
UPDATE employees
SET salary = 50000
WHERE employee_id = 5;</code></pre>
        <p class="text-sm text-yellow-300 mt-2">💡 Always test with SELECT first</p>
    </div>
</div>
                `
            },

            delete: {
                title: "DELETE Statement",
                subtitle: "Removing data from tables",
                content: `
<div class="space-y-4">
    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">Basic DELETE</h3>
        <pre><code>-- Delete specific row
DELETE FROM employees
WHERE name = 'Alice';

-- Delete multiple rows
DELETE FROM orders
WHERE order_date < '2020-01-01';</code></pre>
    </div>

    <div class="bg-red-500/20 border border-red-500/30 rounded-lg p-4">
        <h3 class="text-lg font-bold mb-2">🚨 EXTREME CAUTION</h3>
        <p class="text-sm mb-2">Forgetting WHERE deletes ALL rows!</p>
        <pre><code>-- CATASTROPHIC - Deletes everything!
DELETE FROM employees;

-- SAFE - Deletes specific rows
DELETE FROM employees
WHERE employee_id = 10;</code></pre>
        <p class="text-sm text-yellow-300 mt-2">💡 ALWAYS use WHERE with DELETE</p>
    </div>

    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">Safety Tips</h3>
        <ul class="text-sm space-y-2">
            <li>1. <strong>Test with SELECT first:</strong>
                <pre class="mt-1"><code>-- First, verify what will be deleted
SELECT * FROM employees WHERE department = 'Sales';

-- Then, if correct, delete
DELETE FROM employees WHERE department = 'Sales';</code></pre>
            </li>
            <li>2. <strong>Use transactions</strong> for critical deletes</li>
            <li>3. <strong>Backup</strong> before bulk deletes</li>
            <li>4. Consider using <strong>soft deletes</strong> (status flag) instead</li>
        </ul>
    </div>
</div>
                `
            },

            crud_summary: {
                title: "CRUD Operations Summary",
                subtitle: "Create, Read, Update, Delete",
                content: `
<div class="space-y-4">
    <div class="grid md:grid-cols-2 gap-4">
        <div class="bg-green-500/20 border border-green-500/30 rounded-lg p-4">
            <h3 class="text-lg font-bold mb-2">CREATE (Insert)</h3>
            <pre><code>INSERT INTO table (cols)
VALUES (values);</code></pre>
        </div>

        <div class="bg-blue-500/20 border border-blue-500/30 rounded-lg p-4">
            <h3 class="text-lg font-bold mb-2">READ (Select)</h3>
            <pre><code>SELECT columns
FROM table
WHERE condition;</code></pre>
        </div>

        <div class="bg-yellow-500/20 border border-yellow-500/30 rounded-lg p-4">
            <h3 class="text-lg font-bold mb-2">UPDATE (Modify)</h3>
            <pre><code>UPDATE table
SET column = value
WHERE condition;</code></pre>
        </div>

        <div class="bg-red-500/20 border border-red-500/30 rounded-lg p-4">
            <h3 class="text-lg font-bold mb-2">DELETE (Remove)</h3>
            <pre><code>DELETE FROM table
WHERE condition;</code></pre>
        </div>
    </div>

    <div class="bg-white/10 rounded-lg p-4 mt-4">
        <h3 class="text-xl font-bold mb-2">Complete CRUD Example</h3>
        <pre><code>-- CREATE
INSERT INTO products (name, price, stock)
VALUES ('Laptop', 999.99, 50);

-- READ
SELECT * FROM products WHERE price < 1000;

-- UPDATE
UPDATE products
SET stock = stock - 1
WHERE name = 'Laptop';

-- DELETE
DELETE FROM products
WHERE stock = 0;</code></pre>
    </div>
</div>
                `
            },

            ddl_menu: {
                title: "Data Definition Language (DDL)",
                subtitle: "Define and modify database structure",
                options: [
                    { text: "CREATE TABLE", next: "create_table" },
                    { text: "ALTER TABLE", next: "alter_table" },
                    { text: "DROP & TRUNCATE", next: "drop_truncate" },
                    { text: "DDL Summary", next: "ddl_summary" }
                ]
            },

            create_table: {
                title: "CREATE TABLE",
                subtitle: "Creating new database tables",
                content: `
<div class="space-y-4">
    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">Basic Table Creation</h3>
        <pre><code>CREATE TABLE employees (
    employee_id INT PRIMARY KEY,
    name VARCHAR(50),
    department VARCHAR(50),
    salary DECIMAL(10, 2)
);</code></pre>
    </div>

    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">Common Data Types</h3>
        <div class="grid md:grid-cols-2 gap-2 text-sm">
            <div><code>INT</code> - Integer numbers</div>
            <div><code>DECIMAL(p,s)</code> - Fixed decimal</div>
            <div><code>VARCHAR(n)</code> - Variable string</div>
            <div><code>TEXT</code> - Long text</div>
            <div><code>DATE</code> - Date (YYYY-MM-DD)</div>
            <div><code>DATETIME</code> - Date and time</div>
            <div><code>BOOLEAN</code> - True/False</div>
            <div><code>BLOB</code> - Binary data</div>
        </div>
    </div>

    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">Table with Constraints</h3>
        <pre><code>CREATE TABLE customers (
    customer_id INT PRIMARY KEY AUTO_INCREMENT,
    first_name VARCHAR(50) NOT NULL,
    last_name VARCHAR(50) NOT NULL,
    birth_date DATE,
    phone VARCHAR(15),
    address TEXT,
    city VARCHAR(50),
    state VARCHAR(50),
    points INT DEFAULT 0,
    created_at DATETIME DEFAULT CURRENT_TIMESTAMP,
    UNIQUE (phone)
);</code></pre>
    </div>

    <div class="bg-green-500/20 border border-green-500/30 rounded-lg p-4">
        <h3 class="text-lg font-bold mb-2">💡 Key Tips</h3>
        <ul class="text-sm space-y-1">
            <li>• Use <code>NOT NULL</code> for mandatory fields</li>
            <li>• <code>AUTO_INCREMENT</code> for primary keys</li>
            <li>• <code>DEFAULT</code> values help maintain consistency</li>
            <li>• <code>UNIQUE</code> ensures no duplicate values in a column</li>
        </ul>
    </div>
</div>
                `
            },

            alter_table: {
                title: "ALTER TABLE",
                subtitle: "Modify existing tables",
                content: `
<div class="space-y-4">
    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">Add Column</h3>
        <pre><code>ALTER TABLE customers
ADD email VARCHAR(100) UNIQUE;</code></pre>
    </div>

    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">Modify Column</h3>
        <pre><code>ALTER TABLE customers
MODIFY COLUMN phone VARCHAR(20) NOT NULL;</code></pre>
    </div>

    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">Drop Column</h3>
        <pre><code>ALTER TABLE customers
DROP COLUMN address;</code></pre>
    </div>

    <div class="bg-green-500/20 border border-green-500/30 rounded-lg p-4">
        <h3 class="text-lg font-bold mb-2">✅ Best Practices</h3>
        <ul class="text-sm space-y-1">
            <li>• Backup tables before major changes</li>
            <li>• Add columns at the end to avoid breaking queries</li>
            <li>• Rename columns carefully (use <code>CHANGE COLUMN</code> in MySQL)</li>
        </ul>
    </div>
</div>
                `
            },

            drop_truncate: {
                title: "DROP & TRUNCATE",
                subtitle: "Remove tables or clear data",
                content: `
<div class="space-y-4">
    <div class="bg-red-500/20 border border-red-500/30 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">DROP TABLE</h3>
        <pre><code>-- Deletes the table completely (structure + data)
DROP TABLE customers;</code></pre>
        <p class="text-sm text-yellow-300 mt-2">⚠️ Irreversible! Use carefully.</p>
    </div>

    <div class="bg-red-500/20 border border-red-500/30 rounded-lg p-4">
        <h3 class="text-xl font-bold mb-2">TRUNCATE TABLE</h3>
        <pre><code>-- Deletes all rows but keeps table structure
TRUNCATE TABLE customers;</code></pre>
        <p class="text-sm text-yellow-300 mt-2">⚠️ Fast but cannot be rolled back in some databases.</p>
    </div>

    <div class="bg-green-500/20 border border-green-500/30 rounded-lg p-4">
        <h3 class="text-lg font-bold mb-2">💡 Tip</h3>
        <ul class="text-sm space-y-1">
            <li>• Use <code>DROP</code> if you want to remove the table entirely</li>
            <li>• Use <code>TRUNCATE</code> to quickly clear all data while keeping structure</li>
        </ul>
    </div>
</div>
                `
            },

            joins_menu: {
                title: "Joins & Relationships",
                subtitle: "Combine data from multiple tables",
                options: [
                    { text: "INNER JOIN", next: "inner_join" },
                    { text: "LEFT JOIN", next: "left_join" },
                    { text: "RIGHT JOIN", next: "right_join" },
                    { text: "FULL OUTER JOIN", next: "full_outer_join" },
                    { text: "SELF JOIN", next: "self_join" },
                    { text: "CROSS JOIN", next: "cross_join" }
                ]
            },

            inner_join: {
                title: "INNER JOIN",
                subtitle: "Return matching rows from both tables",
                content: `
<div class="space-y-4">
    <div class="bg-white/10 rounded-lg p-4">
        <pre><code>SELECT e.name, d.department_name
FROM employees e
INNER JOIN departments d
ON e.department_id = d.id;</code></pre>
        <p class="text-sm text-gray-300 mt-2">Only rows with matching department_id appear.</p>
    </div>
</div>
                `
            },

            left_join: {
                title: "LEFT JOIN",
                subtitle: "Return all rows from the left table",
                content: `
<div class="space-y-4">
    <div class="bg-white/10 rounded-lg p-4">
        <pre><code>SELECT e.name, d.department_name
FROM employees e
LEFT JOIN departments d
ON e.department_id = d.id;</code></pre>
        <p class="text-sm text-gray-300 mt-2">All employees shown; unmatched departments appear as NULL.</p>
    </div>
</div>
                `
            },

            right_join: {
                title: "RIGHT JOIN",
                subtitle: "Return all rows from the right table",
                content: `
<div class="space-y-4">
    <div class="bg-white/10 rounded-lg p-4">
        <pre><code>SELECT e.name, d.department_name
FROM employees e
RIGHT JOIN departments d
ON e.department_id = d.id;</code></pre>
        <p class="text-sm text-gray-300 mt-2">All departments shown; unmatched employees appear as NULL.</p>
    </div>
</div>
                `
            },

            full_outer_join: {
                title: "FULL OUTER JOIN",
                subtitle: "Return all rows from both tables",
                content: `
<div class="space-y-4">
    <div class="bg-white/10 rounded-lg p-4">
        <pre><code>SELECT e.name, d.department_name
FROM employees e
FULL OUTER JOIN departments d
ON e.department_id = d.id;</code></pre>
        <p class="text-sm text-gray-300 mt-2">All employees and departments shown; unmatched entries appear as NULL.</p>
    </div>
</div>
                `
            },

            self_join: {
                title: "SELF JOIN",
                subtitle: "Join a table to itself",
                content: `
<div class="space-y-4">
    <div class="bg-white/10 rounded-lg p-4">
        <pre><code>SELECT e1.name AS Employee, e2.name AS Manager
FROM employees e1
LEFT JOIN employees e2
ON e1.manager_id = e2.employee_id;</code></pre>
        <p class="text-sm text-gray-300 mt-2">Useful for hierarchical or recursive relationships.</p>
    </div>
</div>
                `
            },

            cross_join: {
                title: "CROSS JOIN",
                subtitle: "Return all combinations of rows",
                content: `
<div class="space-y-4">
    <div class="bg-white/10 rounded-lg p-4">
        <pre><code>SELECT e.name, d.department_name
FROM employees e
CROSS JOIN departments d;</code></pre>
        <p class="text-sm text-gray-300 mt-2">Every employee combined with every department.</p>
    </div>
</div>
                `
            },

            examples: {
                title: "Practice Examples",
                subtitle: "Try queries yourself",
                content: `
<div class="space-y-4">
    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-lg font-bold mb-2">1. Top 5 Highest Paid Employees</h3>
        <pre><code>SELECT name, salary
FROM employees
ORDER BY salary DESC
LIMIT 5;</code></pre>
    </div>

    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-lg font-bold mb-2">2. Total Sales by Customer</h3>
        <pre><code>SELECT c.first_name, c.last_name, SUM(o.amount) AS total_sales
FROM customers c
JOIN orders o ON c.customer_id = o.customer_id
GROUP BY c.customer_id;</code></pre>
    </div>

    <div class="bg-white/10 rounded-lg p-4">
        <h3 class="text-lg font-bold mb-2">3. Customers with No Orders</h3>
        <pre><code>SELECT c.first_name, c.last_name
FROM customers c
LEFT JOIN orders o ON c.customer_id = o.customer_id
WHERE o.order_id IS NULL;</code></pre>
    </div>
</div>
                `
            }

        };

        // Render function (simplified)
        const app = document.getElementById('app');

        function render(topicKey) {
            const topic = sqlTopics[topicKey];
            app.innerHTML = `
                <div class="p-4 space-y-6">
                    <h1 class="text-3xl font-bold mb-2">${topic.title}</h1>
                    <h2 class="text-xl mb-4 text-gray-300">${topic.subtitle || ''}</h2>
                    <div>${topic.content || ''}</div>
                    <div class="space-y-2 mt-6">
                        ${(topic.options || []).map(opt => `<button class="bg-blue-600 hover:bg-blue-700 px-4 py-2 rounded text-white" onclick="render('${opt.next}')">${opt.text}</button>`).join('')}
                    </div>
                    <div class="mt-6">
                        <button class="bg-gray-600 hover:bg-gray-700 px-4 py-2 rounded text-white" onclick="render('start')">🏠 Back to Main Menu</button>
                    </div>
                </div>
            `;
        }

        render('start');
    </script>
</body>
</html>
