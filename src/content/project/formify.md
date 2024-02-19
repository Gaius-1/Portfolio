---
title: Drag n Drog Form Builder
tags: [NextJS, TailwindCSS, postgreSQL]
image:
  src: /images/formify.png
  alt: ""
timestamp: 2023-12-19
description: Formify is an interactive, cutting-edge Drag & Drop Form Builder built to enable users to design forms faster.
demoLink: https://formify-navy.vercel.app/
---

# Formify

![Formify Logo](/images/formify.png)

Formify is an interactive, cutting-edge Drag-and-Drop Form Builder project built with Next.js 13, the Dnd-kit library, ServerActions, Typescript, Tailwindcss/Shadcn UI, Vercel PostgreSQL, and Prisma as an ORM. This powerful solution is tailored specifically for insurance document creation and other insurance-related forms, empowering insurance professionals to design, customize, and regenerate intricate forms seamlessly.

**NB: Use PC to view to get the best user interaction**

## Features

- **Responsive**: Ensures a seamless experience across various devices.
- **Drag-and-Drop Designer**: Create forms effortlessly with a stunning drag-and-drop interface.
- **Layout Fields**: Include Title, SubTitle, Spacer, Separator, and Paragraph elements to structure your forms precisely.
- **Form Fields**: Utilize Text, Number, Select, Date, Checkbox, and Textarea fields to capture diverse information.
- **Customizable**: Easily add and customize new fields to meet your specific requirements.
- **Form Preview Dialog**: Preview your form in real-time during the design phase.
- **Shareable Form URL**: Share your forms with stakeholders using a unique URL.
- **Form Submission/Validation**: Implement robust submission and validation processes.
- **Form Stats**: Track form visits and submissions to gather valuable insights.

## Technologies Used

- **Next.js 13 with AppRouter**: Leveraging the latest features of Next.js for a seamless development experience.
- **Dnd-kit Library**: Enabling smooth drag-and-drop interactions in the form builder.
- **ServerActions**: Facilitating server-side actions for enhanced functionality.
- **Typescript**: Ensuring type safety and improved code quality.
- **Tailwindcss/Shadcn UI**: Employing a modern and customizable UI framework.
- **Vercel PostgreSQL**: Utilizing Vercel for deployment and PostgreSQL for robust data storage.
- **Prisma as ORM**: Simplifying database interactions with Prisma.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Gaius-1/formify.git
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Set Environment Variables:**
    ```.env
    # Clerk Project Dashboard
    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
    CLERK_SECRET_KEY=
    NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
    NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
    NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
    NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

    # Database URL
    POSTGRES_PRISMA_URL=""
    POSTGRES_URL_NON_POOLING=""
    ```

4. **Run the Development Server:**
   ```bash
   npm run dev
   ```

4. **Open Your Browser:**
   Visit [http://localhost:3000](http://localhost:3000) to explore Formify.

## Usage
Formify offers a range of features to streamline the form-building process, making it an ideal choice for insurance professionals. From a responsive design to a rich set of form customization options, Formify has everything you need to create and manage intricate forms effortlessly.

<!-- ## Screenshots

### Form Creation UI
![Form Creation UI](./public/form-creation.png)

### Form Preview
![Form Preview](./public/form-preview.png) -->

## Contributing

We welcome contributions from the community. Feel free to open issues, submit pull requests, or provide feedback to help make Formify even better.

Happy Form Building! 🚀