<script>
    import Experience from "components/Experience";
    import Section from "components/Section";
    import SubSection from "components/SubSection";
    import Rating from "components/Rating";

    const bgcol = "#faf8e8";
    const footerbgcol = "#555555";
    const footertcol = "#cccccc";
</script>

<style type="text/scss">

    .index-wrapper {
        width: 100%;
    }

    #aboutme-content {
        margin-top: 50px;
        display: flex;
        flex-wrap: wrap;
        justify-content: center;

        p {
            margin-top: 5px;
            max-width: 400px;
        }
        
        img {
            max-width: 250px;
            margin-left: 10px;
        }
    }
</style>

<div class="index-wrapper">
    <Section {bgcol}>
        <span slot="title">About Me</span>
        <span slot="text">
            <div id="aboutme-content">
                <p>
                    I currently study Computer Science at the Technical University of Denmark (DTU).
                    I work as a student helper at Siemens where I'm working on a variety of projects, but I typically make websites.
                    <br>
                    In my spare time I enjoy spending time on my projects, workout and play the piano.
                </p>
                <img src="/img/me.jpg" alt="My image"/>
            </div>
        </span>
    </Section>
    <Section>
        <span slot="title">Experiences</span>
        <span slot="content">
            <SubSection>
                <span slot="title">Educations</span>
                <span slot="content">
                    <Experience>
                        <span slot="location">Technical University of Denmark, Lyngby</span>
                        <span slot="title">M.Sc in Computer Science and Engineering</span>
                        <span slot="time">2019 - now</span>
                        <span slot="description">
                            I'm currently studing my Master's degree at first semester, and haven't finished any courses yet.
                            <br>
                            My courses currently vary from computer graphics to deep learning.
                        </span>
                    </Experience>
                    <Experience>
                        <span slot="location">Technical University of Denmark, Lyngby</span>
                        <span slot="title">B.Sc in Software Technology</span>
                        <span slot="time">2016 - 2019</span>
                        <span slot="description">
                            While studying Software Technology, I chose to focus my courses on AI.
                            <br>
                            My thesis had the title <i>Artificial Intelligence in Multi-Agent Systems</i>.
                        </span>
                    </Experience>
                </span>
            </SubSection>
            <SubSection>
                <span slot="title">Careers</span>
                <span slot="content">
                    <Experience>
                        <span slot="location">Siemens, Ballerup</span>
                        <span slot="title">Student Helper</span>
                        <span slot="time">2018 - now</span>
                        <span slot="description">
                            I help the employees in Siemens in various ways.
                            <br>
                            Usually I'm making websites to make life easier, either back-end or front-end, sometimes full-stack.
                            <br>
                            Besides websites I also help making Excel formulas or write macros using VBA.
                            Other times I speed up a process by writing a small Python-app.
                        </span>
                    </Experience>
                </span>
            </SubSection>
            <SubSection>
                <span slot="title">Projects</span>
                <span slot="content">
                    I enjoy working out and working on my personal
                    <a target="_blank" href="https://github.com/NikRadi">projects</a>.
                    My projects typically have an AI-theme, and may vary from
                    <a target="_blank" href="https://github.com/NikRadi/Kasparov2">chess bots</a>
                    to simple
                    <a target="_blank" href="https://github.com/NikRadi/SimpleNeuralNetPy">deep learning</a> projects.
                </span>
            </SubSection>
        </span>
    </Section>
    <Section {bgcol}>
        <span slot="title">Skills</span>
        <span slot="content">
            <SubSection>
                <span slot="title">Programming, Scripting and Markup Languages</span>
                <span slot="content">
                    <Rating rating={5}>c++</Rating>
                    <Rating rating={5}>C#</Rating>
                    <Rating rating={5}>Python</Rating>
                    <Rating rating={4}>HTML / CSS</Rating>
                    <Rating rating={3}>SASS / SCSS</Rating>
                    <Rating rating={3}>c</Rating>
                    <Rating rating={3}>Java</Rating>
                    <Rating rating={3}>SQL</Rating>
                    <Rating rating={3}>VBA</Rating>
                    <Rating rating={2}>Javascript</Rating>
                    <Rating rating={2}>Prolog</Rating>
                    <Rating rating={1}>F#</Rating>
                    <Rating rating={1}>R</Rating>
                </span>
            </SubSection>
            <SubSection>
                <span slot="title">Frameworks</span>
                <span slot="content">
                    <Rating rating={4}>Flask</Rating>
                    <Rating rating={4}>Svelte</Rating>
                </span>
            </SubSection>
            <SubSection>
                <span slot="title">Tools</span>
                <span slot="content">
                    <Rating rating={4}>Git</Rating>
                    <Rating rating={3}>SQLite</Rating>
                    <Rating rating={2}>PostgresSQL</Rating>
                </span>
            </SubSection>
        </span>
    </Section>
    <Section bgcol={footerbgcol} tcol={footertcol}>
        <span slot="title">Contact</span>
    </Section>
</div>