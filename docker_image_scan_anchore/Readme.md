```yaml
      - name: "DOCKER:SCAN:ANCHORE"
        uses: enzyme-health/devops.github-actions/docker_image_scan_anchore@main
        with:
          docker_image_name: "{{ env.docker_image_name }}"
```