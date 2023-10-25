<script>
    import { dues } from '$lib/utils/helper';
    let one, oneOne, oneOneOne, oneTwo, oneTwoOne, oneTwoTwo, oneTwoThree, oneTwoFour, oneTwoFive, oneThree;
    let two, twoOne, twoTwo, twoThree;
    let three, threeOne;
    let four, fourOne, fourTwo;
    let five, fiveOne;
    let six, sixOne, sixTwo, sixThree;
    let seven, sevenOne, sevenTwo, sevenThree;

    const goToSection = (section) => {
        const top = section.getBoundingClientRect().top + window.pageYOffset;
        window.scrollTo({left: 0, top, behavior: 'smooth'});
    }
</script>

<style>
    .constitution {
        position: relative;
        z-index: 1;
        width: 92%;
        max-width: 800px;
        margin: 8em auto 10em;
    }

    h1 {
        font-size: 2em;
        line-height: 1.2em;
        text-align: center;
        margin: 2em 0 1.5em;
    }

    h2 {
        font-size: 1.5em;
        line-height: 1.2em;
    }

    h3 {
        text-decoration: underline;
        font-size: 1.3em;
        line-height: 1.2em;
    }

    h4 {
        text-decoration: underline;
        margin-left: 2em;
        font-size: 1.2em;
        line-height: 1.2em;
    }

    h5 {
        margin-left: 6em;
        font-size: 0.8em;
        line-height: 1.1em;
    }

    .subBlock {
        margin-left: 2.4em;
    }

    .sectionHeading {
        margin: 4em 0 1.5em;
    }

    .subSectionHeading {
        margin: 1.5em 0 1.5em;
    }

    .underscore {
        text-decoration: underline;
    }

    .right {
        text-align: right;
    }

    .positionMaximums td {
        min-width: 3em;
    }

    .noUnderscore {
        text-decoration: none;
    }

    .clickable {
        cursor: pointer;
    }

    .clickable:hover {
        color: #00316b;
    }

    p {
        color: #777;
    }
</style>

<div class="constitution">
    <h1 class="noUnderscore">LIVE NASTY DY NASTY CONSTITUTION</h1>
    
    <h2 class="noUnderscore">TABLE OF CONTENTS</h2>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(one)}>Section 1: League Size and Structure</h3>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(two)}>Section 2: Roster and Team Composition</h3>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(three)}>Section 3: Taxi Squads</h3>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(four)}>Section 4: Scoring</h3>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(five)}>Section 5: Start-up Draft</h3>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(six)}>Section 6: Yearly Supplementary Draft</h3>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Section 7: Trading</h3>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(eight)}>Section 8: Waivers and Free Agents</h3>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(nine)}>Section 9: Season Schedule</h3>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(ten)}>Section 10: Prize Pool and Punishments</h3>
    
    <hr />
    
    <h2 class="sectionHeading" bind:this={one}>Section 1: League Size and Structure</h2>
    
    <p><strong>1.01</strong> Live Nasty, Dy Nasty is a dynasty league of 12 Teams made up of 3 Divisions of 4 Teams each</p>
    
    <p><strong>1.02</strong> The teams assigned to each division will be done so randomly at the start of every season</p>
   
    <p class="subBlock"><strong>1.02.01</strong> The teams agreed from maining contant divisions from the start of season 2</p>

    <h2 class="sectionHeading" bind:this={two}>Section 2: Roster and Team Composition</h2>
    
    <p><strong>2.01</strong> Each roster contains a maximum of 30 players, with an additional 5 Taxi Squad spots available</p>
    
    <p><strong>2.02</strong> There will be 3 Injured Reserved slots per team to store players that have been designated to the IR or Covid list by their NFL team</p>
    
    <p><strong>2.03</strong> Starting lineup structure is as follows:</p>
    <ul>
        <li>1 x QB</li>
        <li>2 x RB</li>
        <li>2 x WR</li>
        <li>1 x TE</li>
        <li>1 x Flex (RB/WR/TE)</li>
        <li>1 x Superflex (QB/RB/WR/TE)</li>
        <li>1 x Kicker</li>
        <li>1 x DL</li>
        <li>1 x LB</li>
        <li>1 x DB</li>
    </ul>

    <h2 class="sectionHeading" bind:this={three}>Section 3: Taxi Squads</h2>
    
    <p><strong>3.01</strong> There are 5 Taxi Squad slots for each team</p>
    
    <p><strong>3.02</strong> Only Rookies can be added to the Taxi Squad</p>

    <p><strong>3.03</strong> Players can be moved into the taxi squad until the regular season starts. Once the deadline passes, players can no longer be moved into the taxi squad.</p>

    <p><strong>3.04</strong> Players can be kept on a Taxi Squad for 2 Seasons. After this time they must be either activated to your main roster or dropped.</p>

    <p><strong>3.05</strong> Taxi squad size is increased to 10 between season. It is reduced back to 5 before the first NFL game of the season kicks off</p>

<h2 class="sectionHeading" bind:this={four}>Section 4: Scoring</h2>
    
    <p><strong>4.01</strong> The scoring format will be default PPR options</p>
    
    <p><strong>4.02</strong> Passing scoring:</p>
    <ul>
        <li>Passing yards: 1 point every 25 yards</li>
        <li>Passing TD: 4 points</li>
        <li>2-point conversion: 2 points</li>
        <li>Interception: -1 point</li>
    </ul>

    <p><strong>4.03</strong> Rushing scoring:</p>
    <ul>
        <li>Rushing yards: 1 point every 10 yards</li>
        <li>Rushing TD: 6 points</li>
        <li>2-point conversion: 2 points</li>
    </ul>

    <p><strong>4.04</strong> Receiving scoring:</p>
    <ul>
        <li>Reception: 1 point</li>
        <li>Receiving yards: 1 point every 10 yards</li>
        <li>Receiving TD: 6 points</li>
        <li>2-point conversion: 2 points</li>
    </ul>

    <p><strong>4.05</strong> Kicking scoring:</p>
    <ul>
        <li>FG made (0-39 yards): 3 points</li>
        <li>FG made (40-49 yards): 4 points</li>
        <li>FG made (50+ yards): 5 points</li>
        <li>PAT made: 1 point</li>
        <li>FG missed: -1 point</li>
        <li>PAT missed: -1 point</li>
    </ul>

    <p><strong>4.06</strong> Special teams scoring:</p>
    <ul>
        <li>Special teams player TD: 6 points</li>
        <li>Special teams player forced fumble: 1 point</li>
        <li>Special teams player fumble recovery: 1 point</li>
    </ul>

    <p><strong>4.07</strong> Misc scoring:</p>
    <ul>
        <li>Fumble: -1 point</li>
        <li>Fumble lost: -2 points</li>
        <li>Fumble recovery TD: 6 points</li>
    </ul>

    <p><strong>4.08</strong> IDP scoring:</p>
    <ul>
        <li>IDP TD: 6 points</li>
        <li>Sack: 6 points</li>
        <li>Hit on QB: 1 point</li>
        <li>Tackle for loss: 2 points</li>
        <li>Blocked punt, PAT or FG: 3 points</li>
        <li>Interception: 6 points</li>
        <li>Fumble recovery: 3 points</li>
        <li>Forced fumble: 3 points</li>
        <li>Safety: 3 points</li>
        <li>Assisted tackle: 1 point</li>
        <li>SSolo tackle: 2 points</li>
        <li>Pass defended: 3 points</li>
    </ul>

    <h2 class="sectionHeading" bind:this={five}>Section 5: Start-up Draft</h2>
    
    <p><strong>5.01</strong> The start up draft will be a 30 round snake draft</p>
    
    <p><strong>5.02</strong> The draft will occur over 3 separate sessions of 10 rounds each (dates and times TBD)</p>

    <p><strong>5.03</strong> The draft will take place between the start of NFL free agency and the NFL Draft (between 17th March - 29th April)</p>

    <p><strong>5.04</strong> The draft order will be generated randomly in advance of the draft</p>

    <p><strong>5.05</strong> The first season Rookie Draft will be a separate, 3-round event after the NFL draft. This will also be a snake draft and the draft order will be the reverse of the initial start-up draft order</p>

    <h2 class="sectionHeading" bind:this={six}>Section 6: Yearly Supplementary Draft</h2>
    
    <p><strong>6.01</strong> Before each season there will be a supplementary draft for all new Rookies and Free Agents</p>
    
    <p><strong>6.02</strong> The Supplementary Draft will contain 3 rounds</p>

    <p class="subBlock"><strong>6.02.01</strong> It was agreed this would be extended to 5 rounds due to the impact of IDP picks</p>

    <p><strong>6.03</strong> Draft order for non-playoff teams is decided by total seasonal points for full end of season roster (including bench spots) and then play off elimination round and reverse regular season standings order for playoff teams.</p>

    <p class="subBlock"><strong>6.03.01</strong> The draft order for non-playoff teams has been changed to be based on max potential points for.</p>

    <p><strong>6.04</strong> The supplementary draft will not be a snake draft. The draft order will be maintained between rounds</p>

    <h2 class="sectionHeading" bind:this={seven}>Section 7: Trading</h2>
    
    <p><strong>7.01</strong> Trades can be made between teams at any point in the year. There will be no trade deadline</p>
    
    <p><strong>7.02</strong> Trades can be made using any combinations of either players or future draft picks</p>

    <p><strong>7.03</strong> Future draft picks can only be traded for the subsequent 3 drafts</p>

    <p><strong>7.04</strong> Trades can be made during the drafts</p>

    <p><strong>7.05</strong> Start Up Draft picks can be traded once the draft order has been set</p>

    <p><strong>7.06</strong> Trading can commence once all participants have joined the league and the start up draft order has been set</p>

    <p><strong>7.07</strong> Every player has the right to make any trade they want, as such there will be no votes to veto any trades made. The co-commissioners may step in to veto a trade only in severe and obvious instances of collusion or tanking to preserve the integrity of the league</p>

</div>
