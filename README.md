# Design Philosophies

### Compound interest works in everything

<details><summary>Explanation</summary>
<p>

Regularly refactoring code, improving readability, and optimizing performance
might seem insignificant day-to-day, but over time, these small enhancements
compound. The codebase becomes more maintainable, easier to understand, and less
prone to bugs.

</p>
</details>

### "Make things as simple as possible, but not simpler". Don't make things easy to do, make them easy to be used and understand

<details><summary>Explanation</summary>
<p>

Simplicity in Design. Avoid Over-Engineering. Ensure the design is
straightforward without unnecessary complexities. For example, don't add
features that are not needed by the users or the system.

Clarity. The design should be clear and concise, making it easy for other
developers to understand and maintain the code.

User-Centric Design. Focus on making the software easy to use and understand for
the end-user, rather than just easy to build. This involves intuitive
interfaces, clear documentation, and helpful error messages.

Avoiding Over-Simplification. Don't oversimplify to the point where the software
no longer meets the needs of the users or becomes less reliable.

</p>
</details>

### Make a prototype as soon as possible and run it in production. Technical debt = company pays for nothing

<details><summary>Explanation</summary>
<p>

Early Feedback. Creating a prototype quickly and deploying it in production
allows for early user feedback. This helps in identifying potential issues,
understanding user needs, and making necessary adjustments before investing
heavily in development.

Iterative Improvement. By getting a working version into production early,
developers can iterate and improve based on real-world usage and feedback. This
can lead to a more refined and useful final product.

Technical debt refers to the implied cost of additional rework caused by
choosing an easy, limited, or suboptimal solution now instead of using a better
approach that would take longer. It accumulates when quick fixes, shortcuts, or
poor design decisions are made.

Costs of Technical Debt. Over time, technical debt can lead to increased
maintenance costs, slower development, and higher bug rates. This can result in
the company spending more resources on fixing problems rather than adding value,
hence "paying for nothing."

</p>
</details>

### Each software application should do one thing very well

<details><summary>Explanation</summary>
<p>

Single Responsibility. Each application should have a clear and focused purpose.
By doing one thing very well, the software can be more robust, easier to
maintain, and less prone to bugs.

Avoiding Bloat. Applications should avoid feature creep, which can make them
more complex, harder to use, and more difficult to maintain. Focus on the core
functionality and do it exceptionally well.

Modularity and Composition. Interoperability: Small, focused applications can
work together seamlessly. This modular approach allows developers to compose
complex systems from simple, well-defined components. Reusable Components: When
applications do one thing very well, they can be reused in different contexts,
increasing their value and reducing redundant development efforts.

Maintainability. Easier Debugging: With a clear and focused scope, identifying
and fixing issues becomes easier. Developers can quickly understand the
application’s purpose and logic. Simplified Testing: Testing a single-function
application is more straightforward than testing a multifaceted system. This
ensures higher reliability and quality.

</p>
</details>

### Avoid fancy UX, focus on usability

<details><summary>Explanation</summary>
<p>

Prioritizing Functionality. Focus on what users need to accomplish their tasks
efficiently and effectively. Ensure the interface supports these tasks without
unnecessary distractions.

</p>
</details>
