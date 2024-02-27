# pipelineexample
GitHub Actions Workflow

- run: echo "💡 The ${{ github.repository }} repository has been cloned to
the runner."
- run: echo "🖥 The workflow is now ready to test your code on the runner."
- name: List files in the repository
run: |
ls ${{ github.workspace }}
- run: echo "🍏 This job's status is ${{ job.status }}."
