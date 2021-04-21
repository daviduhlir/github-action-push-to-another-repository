# Fork
This is fork of cpina/github-action-push-to-another-repository I forked this repository because I neded to add tag into commit.
Everything other in this repository is only copy of original repository. Thanks for that.


## Example usage
```yaml
      - name: Pushes to another repository
        uses: daviduhlir/github-action-push-to-another-repository@master
        env:
          API_TOKEN_GITHUB: ${{ secrets.API_TOKEN_GITHUB }}
        with:
          source-directory: 'output'
          destination-github-username: 'cpina'
          destination-repository-name: 'pandoc-test-output'
          user-email: carles3@pina.cat
```
