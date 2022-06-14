```yaml
      - name: "DOCKER:BUILD:CHECK:PUSH"
        uses: enzyme-health/devops.github-actions/docker_build_check_push@main
        with:
          docker_image_name: "{{ env.docker_image_name }}"
          docker_file_location: "."
```