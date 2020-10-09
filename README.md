# getyourvoting.guide

Get your Election 2020 Voting Guide here! The voting guides included are progressive minded voting guides to help you in casting your ballot for USA Election 2020 on November 3 2020.

## Add a voting guide

If you have a voting guide you would like to add, open a pull request and include the following information in the `index.html`:

- Link to voting guide
- Explanation if it is partisan or not

Example you are adding a voting a guide to a state that doesn't exist:

```
          <div class="panel panel-default">
            <div class="panel-heading">
              <h4 class="panel-title panel-title-adjust"><a data-toggle="collapse" data-parent="#accordion" href="#collapseten"><i class="material-icons" style="color:white">outlined_flag</i>New State</a></h4>
            </div>
            <div id="collapseten" class="panel-collapse collapse">
              <div class="panel-body">
                <ul>
                  <li><h3>Non-Partisan Guide<a href="https://link-to-guide.com/"> by organization X</a></h3></li>
                </ul>
            </div>
          </div>
        </div>
```

Note you'll need to include a `href` and a `div id` that matches the `href` value. The value of the `href` should be unique and be the next number in sequence you want the state to appear in: e.g. `collapseten`. 

If the guide you wish to add already has a state listed, simply insert a new `li` with that guide:

```
                  <li><h3>New Non-Partisan Guide<a href="https://link-to-guide.com/"> by organization X</a></h3></li>
```


## Questions & Attributions

You can reach me on [social](https://twitter.com/loooorenanicole) for questions or by opening an issue. To attribute the guide, include a link to the repository. If sharing on social, I'd appreciate a mention with `#GetYourVotingGuide`! 
