# My Tasks - Todo App

A modern, feature-rich todo application with local storage persistence.

## Features

✨ **Full CRUD Operations**
- Create new tasks with custom categories
- Read/view all tasks with multiple filter options
- Update task text with inline editing
- Delete individual tasks or bulk clear completed ones

📦 **Local Storage**
- All tasks persist in browser localStorage
- Data survives page refreshes and browser restarts
- No backend required — works completely offline

🏷️ **Categories**
- Personal (👤)
- Work (💼)
- Shopping (🛒)
- Health (❤️)

🔍 **Advanced Filtering**
- Filter by status: All, Active, Completed
- Filter by category: All categories or specific ones
- Combine filters for precise task management

📊 **Statistics**
- Track active task count
- Monitor completed tasks
- Visual progress indicators

✅ **Task Management**
- Mark tasks as complete/incomplete
- Edit tasks inline with keyboard shortcuts (Enter to save, Escape to cancel)
- Timestamps for when each task was created
- Clear all completed tasks with one click

🎨 **Modern UI**
- Beautiful gradient background
- Smooth transitions and hover effects
- Responsive design for mobile and desktop
- Color-coded categories
- Empty state messages

## How to Use

### Running the App

1. Open `index.html` in any modern web browser.
2. Start adding tasks!

### Using the App

**Adding Tasks**
1. Type your task in the "What needs to be done?" input field.
2. Select a category (Personal, Work, Shopping, or Health).
3. Click "Add Task" or press Enter.

**Managing Tasks**
- **Complete/Uncomplete**: Click the checkbox next to any task.
- **Edit**: Click the edit icon (pencil), make changes, then press Enter or click the checkmark.
- **Delete**: Click the trash icon to remove a task.
- **Clear Completed**: Click "Clear completed tasks" to remove all finished tasks at once.

**Filtering Tasks**
- Use the filter buttons to view All, Active, or Completed tasks.
- Use the category dropdown to filter by specific categories.
- Filters can be combined.

**Keyboard Shortcuts** (while editing)
- `Enter` - Save changes
- `Escape` - Cancel editing

## Technical Details

**Built With**
- HTML, CSS (Tailwind), JavaScript
- LocalStorage API

**Browser Support**
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Any modern browser with ES6+ support

**Data Storage**
All data is stored in browser's localStorage under the key `todos`. The data structure is:

```json
[
  {
    "id": 1234567890,
    "text": "Buy groceries",
    "completed": false,
    "category": "shopping",
    "createdAt": "2024-01-15T10:30:00.000Z"
  }
]
```

## Files Included

- `index.html` - Standalone HTML file (ready to use!)
- `README.md` - This file

## Tips

1. **Organization**: Use categories to keep different types of tasks separate.
2. **Daily Review**: Use the “Active” filter to see what needs to be done today.
3. **Weekly Cleanup**: Use “Clear completed tasks” to remove old completed items.
4. **Mobile Friendly**: The app works great on phones and tablets too!

## Privacy

All your task data stays in your browser’s localStorage. Nothing is sent to any server. Your tasks are completely private and local to your device.

## Future Enhancements (Ideas)

- Due dates and reminders
- Priority levels (high, medium, low)
- Search functionality
- Dark mode
- Export/Import tasks
- Recurring tasks
- Tags/labels
- Drag and drop reordering

## Live Demo

- Check out the live app here: [https://daanyaal5.github.io/to-do_app_list/](https://daanyaal5.github.io/to-do_app_list/)

## License

Free to use and modify as you wish!

---

Enjoy organizing your tasks! 🎉
