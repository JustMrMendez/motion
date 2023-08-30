<script>
    import { Presentation, Slide, Code } from '@components'
  </script>
  
  <Presentation>
  
    <!-- Slide 1: Title Slide -->
    <Slide animate>
      <div class="mx-auto flex-wrap">
        <h1>Introduction to HTML</h1>
        <p>Learn the building blocks of the web.</p>
      </div>
    </Slide>
  
    <!-- Slide 3: Example of an HTML Tag -->
    <Slide animate>
      <div class="mx-auto flex-wrap">
        <Code lang="html" lines="2">
          {`
  <!-- Example of an HTML tag -->
  <p>This is a paragraph.</p>
          `}
        </Code>
      </div>
    </Slide>
  
    <!-- Slide 4: Linking Websites -->
    <Slide animate>
      <div class="mx-auto flex-wrap">
        <Code lang="html" lines="2">
          {`
  <!-- Linking Websites -->
  <a href="https://example.com">Visit Example</a>
          `}
        </Code>
      </div>
    </Slide>
  
    <!-- Slide 5: Audio Tag -->
    <Slide animate>
      <div class="mx-auto flex-wrap">
        <Code lang="html" lines="2-5">
          {`
  <!-- Audio Tag -->
  <audio controls>
    <source src="audio.mp3" type="audio/mp3">
  <\/audio>
          `}
        </Code>
      </div>
    </Slide>
  
    <!-- Slide 6: Exercise Structure -->
    <Slide animate>
      <div class="mx-auto flex-wrap">
        <h2>Exercise Structure</h2>
        <Code lang="markdown" lines="1-3">
          {`
  - \`index.js\`: Entry file for the app.
  - \`README.md\`: Exercise instructions.
  - \`test.js\`: Testing script (no need to open).
          `}
        </Code>
      </div>
    </Slide>
  
    <!-- Slide 7: Final Notes -->
    <Slide animate>
      <div class="mx-auto flex-wrap">
        <h2>Final Notes</h2>
        <Code lang="markdown">
          {`
  The exercises have automatic grading which is very strict. Use them as a suggestion, not as a final test.
          `}
        </Code>
      </div>
    </Slide>
  
  </Presentation>
  