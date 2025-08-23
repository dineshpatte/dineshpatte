// components/AboutMe.tsx
"use client";

export default function AboutMe() {
  return (
    <section className="py-16 px-6 bg-gray-50">
      <div className="max-w-4xl mx-auto">
        {/* Title */}
        <h1 className="text-4xl font-extrabold text-gray-900 mb-4">
          Pattem Guru Dinesh – Full Stack Web Developer
        </h1>

        {/* Intro */}
        <p className="text-lg text-gray-700 leading-relaxed mb-8">
          Hi! I’m <span className="font-medium">Pattem Guru Dinesh</span>, a
          passionate full stack web developer specializing in building modern,
          responsive, and user-friendly web applications.
        </p>

        {/* Skills Section */}
        <div className="space-y-10">
          {/* Frontend */}
          <div>
            <h2 className="text-2xl font-bold text-indigo-600 mb-4">
              Frontend
            </h2>
            <ul className="list-disc list-inside text-gray-700 space-y-2">
              <li>Next.js (SSR, SSG, API routes)</li>
              <li>React.js (functional components, hooks)</li>
              <li>TypeScript (type safety & scalability)</li>
              <li>Tailwind CSS (utility-first responsive styling)</li>
              <li>React Router for smooth client-side navigation</li>
              <li>Clean and accessible UI design with attention to UX</li>
            </ul>
          </div>

          {/* Backend */}
          <div>
            <h2 className="text-2xl font-bold text-indigo-600 mb-4">
              Backend
            </h2>
            <ul className="list-disc list-inside text-gray-700 space-y-2">
              <li>Node.js and Express.js for RESTful API development</li>
              <li>MongoDB for flexible, scalable NoSQL database management</li>
              <li>
                Authentication using JWT and OAuth (where applicable)
              </li>
            </ul>
          </div>

          {/* Other Tools */}
          <div>
            <h2 className="text-2xl font-bold text-indigo-600 mb-4">
              Other Tools & Concepts
            </h2>
            <ul className="list-disc list-inside text-gray-700 space-y-2">
              <li>JavaScript (ES6+), HTML5, CSS3</li>
              <li>
                State management and local storage for temporary data
                persistence
              </li>
              <li>Integration of third-party APIs and libraries</li>
              <li>Responsive design and mobile-first approach</li>
              <li>Version control using Git and GitHub</li>
            </ul>
          </div>
        </div>

        {/* Closing */}
        <p className="mt-10 text-gray-700 leading-relaxed">
          I focus on writing <span className="font-medium">clean, maintainable code</span> 
          with best practices and building full-featured applications that provide 
          <span className="font-medium"> smooth, seamless user experiences</span>.
        </p>

        {/* Contact */}
        <p className="mt-6">
          📧 Feel free to reach out to me via email:{" "}
          <a
            href="mailto:009pattemdinesh@gmail.com"
            className="text-indigo-600 font-medium hover:underline"
          >
            009pattemdinesh@gmail.com
          </a>
        </p>
      </div>
    </section>
  );
}
