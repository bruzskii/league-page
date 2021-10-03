<script context="module">
	export const prerender = true;
</script>

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
        const top = section.getBoundingClientRect().top;
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
    <h1 class="noUnderscore">Drunken Dynasty Bylaws (unofficial)</h1>
    
    <h2 class="noUnderscore">Official league bylaws, with up-to-date changelog and comments, can be found <a href="https://docs.google.com/document/d/1Ju68JXJpY2fGQatjGa22egz_Xs-7oeIx/edit?usp=sharing&ouid=101131312870884818602&rtpof=true&sd=true">here.</a>
</h2>
	
    <h2 class="noUnderscore">Overview</h2>
	<p>All bylaws are an explanation or extension of the rules set on Sleeper. This document doesn’t outline all aspects of the scoring system, or describe how processes on the host websites work. However, any change in rules within the league hosts will be subject to league discussion/vote, as would any rule within the Bylaws.</p>
	
    <h2 class="noUnderscore">TABLE OF CONTENTS</h2>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(one)}>Section 1: Team Setup</h3>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(oneOne)}>1.1 Roster Size</h4>
	<h4 class="noUnderscore clickable" on:click={() => goToSection(oneTwo)}>1.2 Retired Players</h4>
	<h4 class="noUnderscore clickable" on:click={() => goToSection(oneThree)}>1.3 Taxi Squads</h4>
            <h5 class="noUnderscore clickable" on:click={() => goToSection(oneThreeOne)}>1.3.1 Claiming Players</h5>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(two)}>Section 2: Scoring</h3>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(three)}>Section 3: Schedule</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(threeOne)}>3.1 Regular Season</h4>
	<h4 class="noUnderscore clickable" on:click={() => goToSection(threeTwo)}>3.2 Playoffs</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(four)}>Section 4: Rookie Draft</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fourOne)}>4.1 Order of Picks</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(five)}>Section 5: Waivers & Free Agents</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(fiveOne)}>5.1 FAAB</h4>
	<h4 class="noUnderscore clickable" on:click={() => goToSection(fiveTwo)}>5.2 In-Season</h4>
	<h4 class="noUnderscore clickable" on:click={() => goToSection(fiveThree)}>5.3 Offseason</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(six)}>Section 6: Trading</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixOne)}>6.1 General Overview</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixTwo)}>6.2 Veto Power</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(sixThree)}>6.3 Pick Trading Stipulation</h4>

    <h3 class="noUnderscore clickable" on:click={() => goToSection(seven)}>Section 7: Annual Managers Meeting & Rule Changes</h3>
   
    <h3 class="noUnderscore clickable" on:click={() => goToSection(eight)}>Section 8: Dues and Payments</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(eightOne)}>8.1 League Dues</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(eightTwo)}>8.2 Payouts</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(eightThree)}>8.3 Final Payout</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(nine)}>Section 9: Commissioner Responsibilities</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(nineOne)}>9.1 League Dues</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(nineTwo)}>9.2 League Waitlist</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(nineThree)}>9.3 Vice-Commissioner</h4>
    
    <h3 class="noUnderscore clickable" on:click={() => goToSection(ten)}>Section 10: Ethos</h3>
    
        <h4 class="noUnderscore clickable" on:click={() => goToSection(tenOne)}>10.1 Tanking/Abandonment</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(tenTwo)}>10.2 Retirement</h4>
        <h4 class="noUnderscore clickable" on:click={() => goToSection(tenThree)}>10.3 Conclusion</h4>
	
	<hr />
    
    <h2 class="sectionHeading" bind:this={one}>Section 1 Team Setup</h2>
    
    <h3 class="subSectionHeading" bind:this={oneOne}>1.1 Roster Size</h3>
    
    <p>Active Rosters are a maximum of 30 players consisting of 21 bench spots and 9 starters. Starting lineups consist of 1 QB, 2 RBs, 2 WRs, 1 TE, 2 Flex (RB/WR/TE) and 1 Superflex (QB/RB/WR/TE).</p>
    
    <p>No IR spots are made available.</p>

    <p>During the off-season, Sleeper will allow newly-drafted rookies to be placed on active rosters without cutting players. While this is allowed, players are bound by platform rules regarding these overages. Transactions may be restricted by the platform until they are within compliance of platform rules.</p>

    <h3 class="subSectionHeading" bind:this={oneTwo}>1.2 Retired Players</h3>
    
    <p>Should a player retire and remain active on the platform (see Andrew Luck 2019-2020), that player is treated just like any active player. This player will count against the team’s roster space until dropped/traded.</p>
	
    <p>If a retired player is removed from the platform while on an active roster, the manager with that player may place a petition to the commissioner to have that player reinstated as a member of their team should they ever unretire. The petition needs to be placed, and approved, prior to the manager filling the newly-opened spot on their team.</p>    
    
    <h3 bind:this={oneThree}>1.3 Taxi Squads</h3>
    
    <p>Each team is allotted 6 taxi squad spots (as voted on 3/1/21). These spots provide teams with an option to stash rookies or younger players into additional slots that do not count against a team's roster limit. These players cannot be used in your starting lineup unless elevated to the active roster.</p>

    <p>To designate a player to the taxi squad, they must be demoted to the taxi squad on Sleeper prior to the designation deadline, which is currently the start of the regular season. Players cannot be added to taxi squads during the season unless platform rules otherwise allow.</p>

    <p>Rookies and 2nd year NFL players are taxi squad eligible. If a player is promoted during their 1st season, they are allowed, per platform rules, to be placed back on the taxi squad the following offseason. Draft compensation for these players does not change upon a claim. <span class="red">YEAR ONE IS THE EXCEPTION TO THIS RULE - ONLY ROOKIES WILL BE ALLOWED ON THE TAXI SQUAD IN THE 2021 FANTASY SEASON.</span></p> 
	
	<p>Rookies and 2nd year players acquired in the preseason via waivers are taxi-squad eligible in accordance to platform rules.</p>    
	
	<p>Players can be promoted to the active roster at any time. Once a player is on a team’s active roster, they cannot be demoted back to the taxi squad until the following offseason.</p>
	
	<p>Taxi squad players are allowed to be traded off the taxi squad, but they must be placed on the active roster of the receiving team. Sleeper support notes that the sending team should not have to elevate the player to the active roster prior to being traded. However, if the platform ends up requiring this, and thus forcing a drop of another player prior to the trade being made, the sending team will receive the dropped player back after the trade via commissioner action without that player being subject to waivers. However, this must be declared prior to the trade being approved and finalized by the commissioner.</p>
	
	<h4 bind:this={oneThreeOne}>1.2.5 Veto/Trade Process</h4>
    <div class="subBlock">
        <p>A total of 7 veto votes are required to veto a trade. Vetoes are only appropriate in instances of collusion or an egregious mismatch of value (i.e. CMC for a backup kicker). Not liking a trade does not warrant a veto.</p>
    </div>    
    
    <h2 class="sectionHeading" bind:this={two}>Section 2 Drafting</h2>
    
    <h3 bind:this={twoOne}>2.1 Draft Order</h3>
    <p>The draft order each year will be a linear draft in reverse order of the previous year’s regular season standings.</p>

    <h3 bind:this={twoTwo}>2.2 Rookie Drafts</h3>
    <p>Rokkie drafts will consist of 3 round of drafting, with 5 minutes alotted for each pick. To make room for the incoming players, benches will be expanded by (5) spots. These spots will be removed in mid-August, at which point you will need to have cut the necessary players.</p>
    <p>Any spots not filled during the draft, can be filled immediately afterwards from the waiver wire.</p>
    
    <h3 bind:this={twoThree}>2.3 Draft Day Trades</h3>
    <p>If a trade is being made during the draft, one or both parties can alert the commissioner to pause the draft to allow for extra time to negotiate the trade.</p>
    
    <h2 class="sectionHeading" bind:this={three}>Section 3 Scoring System</h2>

    <h3 bind:this={threeOne}>3.1 Scoring System</h3>
    <p>The league scoring system breakdown is listed on the Sleeper fantasy app (for the most part, it follows typical .5PPR Scoring). The scoring system will never change without a majority league vote.</p>
    
    <h2 class="sectionHeading" bind:this={four}>Section 4 Postseason</h2>
    
    <h3 bind:this={fourOne}>4.1 Playoffs</h3>
    <p>At the end of the season 6 teams will make the playoffs. The first round of playoffs will commence in week 15. Each team that wins their division and the 4 wild card teams that finish with the best records, will receive a playoff berth. The 2 teams that win their division will receive a bye week in the first round of the playoffs. Each playoff matchup will only last one week and the winner will advance. Week 18 will not be used.</p>
    
    <h3 bind:this={fourTwo}>4.2 Seeding Tiebreakers</h3>
    <p>If two teams finish with the same record the tiebreakers will go as followed:</p>

    <ol>
        <li>Points For</li>
        <li>Head 2 Head Record</li>
        <li>Division Record</li>
        <li>Total Points Against</li>
        <li>Coin Flip</li>
        <li>Duel to the death</li>
    </ol>

    <h2 class="sectionHeading" bind:this={five}>Section 5 Tanking Policy</h2>
    
    <h3 bind:this={fiveOne}>5.1 League Tanking Policy</h3>
    <p>No team may intentionally leave starting roster spots empty. Any evidence of intentionally leaving roster spots empty in order to improve your draft position may be subject to punishment, including but not limited to the forfeiture of draft selections.</p>

    <h2 class="sectionHeading" bind:this={six}>Section 6 Replacing Managers</h2>
    
    <h3 bind:this={sixOne}>6.1 Removing Managers</h3>
    <p>Short of continuously failing to set a valid lineup, or confirmed collusion, no manager can be removed against their will. Participation, through the league chat, trade offers, and the waiver wire, is strongly encouraged but generally grounds for removal.</p>
    
    <h3 bind:this={sixTwo}>6.2 Replacing Managers</h3>
    <p>When a manager needs to be replaced, the commisiooners will try to find a suitable candidate with some connection to at least a portion of the existing managers. Priority will be placed on managers who are eager to take on a dynasty commitment and will be very active within the league.</p>
    
    <h3 bind:this={sixThree}>6.3 Replacement Incentive</h3>
    <p>In the event that a manager chooses to quit the league or is removed by a comissioner, an incoming manager is offered a 50% reductioon on their first year buy-in.</p>

    <h2 class="sectionHeading" bind:this={seven}>Section 7 League Finances</h2>
    
    <h3 bind:this={sevenOne}>7.1 League Dues</h3>
    <p>League dues are set at {dues}$. Dues are collected through <a href="https://www.leaguesafe.com/league/3949641">LeagueSafe</a> and collection will be sent out no later than the first of August. All managers must be fully paid up before the start of regular season. In the event that a manager fails to pay before the deadline, a 10% penalty will be addd to their payment and will go towards the payouts at the end of the year.</p>
    
    <h3 bind:this={sevenTwo}>7.2 Payout</h3>
    <p>League payout is structured as follows:</p>
    <ul>
        <li>1st place: {dues * 8}$</li>
        <li>2nd place: {dues * 3}$</li>
        <li>3rd place: {dues}$</li>
    </ul>
    <p>In the event that a manager was fined due to late payment, their extra fee will be added to the winner's payout. Similarly, if new managers come into the league and the payout is smaller, the difference will come out of the winner's prize.</p>
    
    <h3 bind:this={sevenThree}>7.3 Raising Dues</h3>
    <p>A ⅔ majority vote is required in order to raise league dues. In the event that a manager is no longer financially comfortable with the buyin, finding a co-manager to split the cost is reccomended.</p>

</div>
