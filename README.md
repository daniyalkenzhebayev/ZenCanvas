ZenCanvas: Smart Hierarchical Planning & Documentation
Project Overview ZenCanvas is a productivity tool designed to bridge the gap between structured task management and free-form note-taking. Unlike traditional list-based apps, ZenCanvas allows users to create an infinite hierarchy of goals, where every node acts as a standalone document for deep planning.
+2
Key Features Implemented

Recursive Task Engine: Developed a custom tree-structure algorithm in Dart that supports infinite nesting of sub-tasks, enabling granular project breakdown.
+1

Dual-Pane Architecture: Engineered a responsive interface where the left panel manages the hierarchy and the right panel serves as a dedicated Rich-Text Editor for each task.

Contextual Data Containers: Each task is designed as a unique data object containing both its position in the tree and its associated markdown-style notes.

Real-time State Management: Implemented an "auto-save" logic using Flutter’s state hooks to ensure note persistence and seamless user flow.
Current Technical Stack

Framework: Flutter (Mobile/Desktop).
Language: Dart.

Version Control: Git.
Future Roadmap
[ ] Integration of an AI-powered "Motivation Engine" to provide contextual quotes based on task progress.

[ ] Local database persistence for offline-first usage.

[ ] Visual "Canvas Mode" for mind-mapping tasks.
